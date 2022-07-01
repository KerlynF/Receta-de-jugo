## Receta de jugo de naranja ##
***

1. Se cortan las naranjas

2. Se exprimen las naranjas en un vaso

3. Se llena una jarra con agua 

4. Se le agrega a la jarra el jugo de naranja en el vaso

5. Se añade hielo y azucar (opcional)

6. Disfrutar!

eveno :: Int -> Bool 
noto  :: Bool -> String 

eveno x = if x `mod` 2 == 0 
   then True 
else False 
noto x = if x == True 
   then "This is an even Number" 
else "This is an ODD number" 

main = do 
   putStrLn "Example of Haskell Function composition" 
   print ((noto.eveno)(16))

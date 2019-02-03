#Platzom
Platzom es un idioma inventado para el [curso de Fundamentos de javascript](http://platzi.com/js) de platzi, el mejor lugar de educación online
## description the Language
-Si la palabra termina en "ar", se le quitan esos dos caracteres
-Si la palabra inicia con Z, se le añade "pe" al final
-Si la palabra traducida tiene 10 o más letras,se debe partir a la mitad y unir con un guión del medio
-Por ultimo si la palabra original es un palíndromo,
ninguna regla anterior cuenta y se devuelve
la misma palabra intercalando mayúsculas y minúsculas.
##Instalación
´´´
npm install platzom
´´´
## Uso
´´´
import platzom from 'platzom'

platzom("Programar")) // Program
platzom("Zorro")) // Zorrope
platzom("Zarpar")) // Zarppe
platzom("abecedario")) // abece-dario
platzom("sometemos")) // SoMeTeMoS
´´´
##Créditos
- [Ricado Rico](http://www.google.com)
##Licencia
[MIT] (https://opensource.org/licenses/MIT)

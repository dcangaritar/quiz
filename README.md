analisis 
03 Validador de Contraseñas
Instrucción:
Desarrolla un programa que valide si una contraseña ingresada por el usuario cumple con los siguientes criterios de seguridad:
Debe tener al menos 8 caracteres
Debe contener al menos una letra mayúscula
Debe contener al menos una letra minúscula
Debe contener al menos un número
Debe contener al menos un carácter especial (@, #, $, %, &, *)
El programa debe indicar cuáles criterios no se cumplen.
Nota: Acá te dejo una ayuda.
(c == '@' || c == '#' || c == '$' || c == '%' || c == '&' || c == '*')

respuesta analisis:

lo primero que se hace es pedirle a un usuario que proporcione una contraseña y se le dan las pautas que debe de seguir 

instrucciones:
Al usuario se le da un scanner para que pueda  ingresar una contraseña.
El programa revisa cada regla de seguridad. Si alguna no se cumple, se añade un mensaje de error.

reglas: 
Debe tener al menos 8 caracteres
Debe contener al menos una letra mayúscula
Debe contener al menos una letra minúscula
Debe contener al menos un número
Debe contener al menos un carácter especial (@, #, $, %, &, *)
El programa debe indicar cuáles criterios no se cumplen.

Resultados:
Si todos los criterios se cumplen, muestra "La contraseña es válida".
Si falta algún criterio, muestra qué falta con un mensaje específico.
- Correr el programa con un debugger, sin agregar flags de
debug. ¿Tienen toda la información que requerían?
no,  el programa add_array_segfault muestra un error pero no nos da informacion del error
- ¿Qué pasa si ponen el flag de debug? ¿Qué flag de optimización es el
mejor para debuggear?
agregando el -O0 -g en el CFLAG (CFLAGS = -O0 -g)logramos que no obtimize y de mas información del error
(lease -O(letra o)0(numero cero)
La suma da un valor de 6 coincide con el valor que debe dar pero hay un error que no podemos ver,
Creamos otro archivo con otra expresion para escribir la suma y detectamos que los indices del for estan mal (n+1 y reemplazamos por n-1)
(for (i = 0; i <= n - 1; i++)) 
- Agreguen algún flag para que informe todos los warnings en la
compilación, como `-Wall`. ¿Alguno les da alguna pista de por qué el
programa se rompe?
En el caso del error del archivo add_array_dynamic.e este flags no encuentra errores
en el caso del programa add_array_segfault  no se general el ejecutable hay un error en la inicializacion de los array 
y esto último lo obtenemos gracias la flags -Wall

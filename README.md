# CHALLENGER ALURA : ENCRIPTADOR DE TEXTO

## Sobre el Encriptador de Texto.
El encriptador de texto se realiza para poner en práctica lo aprendido en el curso de lógica 
de programación de Alura Latam: perfecionar el pensamiento lógico, mejoramiento del análisis
y resolución de problemas expandiendo la visión del mundo del desarrollo.

## Desarrollo
## btnEncriptar:
La encriptación se realiza con las siguientes reglas:

_Las "llaves" de encriptación que utilizaremos son las siguientes: 
- La letra "e" es convertida para "enter"
- La letra "i" es convertida para "imes"
- La letra "a" es convertida para "ai"
- La letra "o" es convertida para "ober"
- La letra "u" es convertida para "ufat"
_y se utilizará el método "replace" para reemplazar las vocales_

## Requisitos
- Debe funcionar solo con letras minúsculas
- No deben ser utilizados letras con acentos ni caracteres especiales:

    /[$\.¿\?~!\¡@#%^&*()_|}\{[\]>\<:"`;,\u0300-\u036f']/g, "" 
- Debe ser posible convertir una palabra para la versión encriptada y también devolver una 
  palabra encriptada para su versión original.

## Extras
- Un botón que copie el texto encriptado/desencriptado para la sección de transferencia, 
  o sea que tenga la misma funcionalidad del ctrl+C o de la opción "copiar" del menú de las 
  aplicaciones.

## btnDesencriptar
Funciona a la inversa que btnEncriptar. Ej; "enter" se reemplaza por "e". Tambien se utilizará el método "replace".

## btnCopiar
Copia el texto del resultado de las encriptaciones.

## Alertas
Va de la mano de la validación de caracteres y envía mensajes si el usuario al momentos de encriptar el texto, no incluye el texto ó ingresa un caracter no permitido.

## Tecnologías

 - ![JavasScript](https://img.shields.io/badge/logo-javascript-blue?logo=javascript)
 - ![HTML5](https://img.shields.io/badge/logo-HTML5-blue?logo=HTML5)
 - ![CSS](https://img.shields.io/badge/logo-CSS-blue?logo=CSS3&logoColor=1572B6)

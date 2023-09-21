# Mi presentación 

Crea un formulario para enviar tu presentación en el curso Full Stack.
Busca en este [enlace](https://www.w3schools.com/html/html_form_elements.asp) los diferentes tipos de controles de formulario que existen para crear todo lo que se te pide en la parte 1

## Parte 1 - Campos que debe tener el formulario

- Nombre. Como mucho tiene 50 carácteres de largo. Campo requerido.
- Edad. Debe ser un número entre 18 y 99. Piensa que existe un control que nos obliga a poner solo números. Campo requerido.
- (DIFÍCIL):  DNI: Excactamente debe tener 9 carácteres. Usa el atributo __pattern__ para formatear el DNI. No tienes porque poner tu dni real... Campo requerido.
- Ciudad de origen. Texto libre de hasta 100 carácteres. Campo requerido.
- Como vienes a estudiar. Es un selector con 3 opciones: A pie, transporte público, trasporte privado. Por defecto, debe estar seleccionado "a pie". Campo requerido.
- Objetivos del curso. Es un texto libre de hasta 1024 carácteres. No es obligatorio.


Si el formulario no cumple alguna de las validaciones NO debe poderse enviar.

## Parte 2 - Configuración del formulario

1. El **atributo** action debe tener por valor el **endpoint** donde vamos a enviar la información. En este caso es: https://singulars2023.free.beeceptor.com
2. El método de envío HTTP debe ser **POST**.
3. Recuerda que es **imprescindible** que cada campo del formulario tenga el atributo **name**; o no se va a enviar ningún tipo de información.

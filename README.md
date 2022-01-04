# Mi presentación en Altia

Crea un formulario para enviar tu presentación en el curso Full Stack.

## Campos que debe tener el formulario

- Nombre. Como mucho tiene 50 carácteres de largo. Campo requerido.
- Edad. Debe ser un número entre 18 y 99. Piensa que existe un control que nos obliga a poner solo números. Campo requerido.
- Ciudad de origen. Texto libre de hasta 100 carácteres. Campo requerido.
- Como vienes a estudiar. Es un selector con 3 opciones: A pie, transporte público, trasporte privado. Por defecto, debe estar seleccionado "a pie". Campo requerido.
- Objetivos del curso. Es un texto libre de hasta 1024 palabras. No es obligatorio.
- 3 cosas sorbe tí. Una de ellas es falsa. Piensa como sería la forma más adecuada de implementar esta información en un formulario.

Si el formulario no cumple alguna de las validaciones NO debe poderse enviar.

## Configuración del formularo

1. El **atributo** action debe tener por valor el **endpoint** donde vamos a enviar la información. En este caso es: https://vigo-rocks.free.beeceptor.com
2. El método de envío HTTP debe ser **POST**.
3. Recuerda que es **imprescindible** que cada campo del formulario tenga el atributo **name**; o no se va a enviar ningún tipo de información.

# platzi-webpack
Repositorio para el código del curso de React.js de Platzi

¿Qué podemos hacer con Webpack?
Qué es Webpack, para qué sirve y por qué deberías tomar este curso.

WP es un Module Bundler for Modern JS Applications, es decir un empaquetador de módulos para el desarrollo de aplicaciones modernas en JavaScript.

¿Por qué usar Webpack?

Aunque hay otras alternativas WP es un la forma mas sofisticada para cargar y transformar módulos. WP trae todas las formas de importación de módulos, en resumen trae lo mejor de todos los mundos.

Entrypoints - múltiples puntos de entrada a tus aplicaciones - archivos iniciales, tienes uno por cada pagina que vayas a usar.

Puedes tener multiples entrypoints.

OUTPUT. Si bien le decimos cual es el archivo fuente, debemos decirle que hacer con eso y donde ponerlo, porque no queremos mezclar los archivos finales que lee el navegador con los archivos fuente.

Loaders. Nos ayudan a cargar todo tipo de formato de archivos.

Plugins. nos ayudan a extender las caracteristicas de WP, por ejemplo comprimir archivos, dividir nuestros modulos en chunks, etc.

WP es developer experience.



## Entry Points
Nuestro módulo principal, de donde se parte a importar los demás módulos. Este es el archivo que leerá webpack para generar el bundle

### Instalación de CLI
Arriba de la versión de Webpack 4 se tiene que instalar el CLI por separado

``` bash
npm install --save-dev webpack-cli
```
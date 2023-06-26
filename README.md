
![Reviw Logo](https://github.com/livrasand/Reviw/assets/104039397/3202a0b1-266c-4815-a4ba-35b470965e7a)


#
Reviw es un lenguaje de marcado de código abierto, escrito en HTML, diseñado para crear documentos, con el objetivo de facilitar el desarrollo de archivos JWPUB. Reviw está basado en JWLV-API que proporciona una interfaz de alto nivel que permite mostrar documentos basados en JWPUB. JWLV-API interpreta el código y lo presenta en pantalla al usuario permitiendo al usuario interactuar con su contenido y navegar idénticamente como lo hace JW Library.

📝 Traducciones disponibles: 🇪🇸

Reviw lo utiliza el editor Sublime Text y próximamente muchas otras aplicaciones.

Este proyecto se adhiere a la licencia GoAttendant Zero Public License. Al participar, se espera que respete este código. Informe cualquier comportamiento inaceptable a livrasand@outlook.com.


## Instalación con Package Control
Instala el empaquetado de Reviw para Sublime Text, para ello ejecuta Command Palette: `Ctrl` + `Shift` + `P`.

Escribe:
```html
Package Control: Install Package
```

Cuando haya cargado Package Control, busque Reviw seguido de `Intro`.
```html
Reviw
```

Esto instalará Reviw en Sublime Text.

## Instalación manual
Si la instalación mediante Package Control no te funciona, prueba la instalación manual:

Ejecuta Command Palette: `Ctrl` + `Shift` + `P`...

Escribe lo siguiente y seguido presiona `Intro`:
```html
Preferences: Browse Packages
```

Esto abrirá una ventana del Explorador de archivos en el directorio de los Packages de Sublime Text. Sube a "Sublime Text" o presiona `Alt` + `↑`.

<img src="https://github.com/livrasand/Reviw/assets/104039397/a887ed2b-2e06-4d90-b536-6bbd159a3bc7" width="500px">

Ahora ve a la carpeta <b>Installed Packages</b>. Ahora solo arrastra o pega el archivo <b>Reviw.sublime-package</b> en esta carpeta. Con esto, automáticamente se instalará Reviw en Sublime Text.

## Solicitar un JWTOKEN para JWBlober
Para recibir solicitudes y enviar los JWTOKENS utilizamos [cabal](https://github.com/cabal-club/cabal-cli)

```html
cabal --save cabal://53c815d8d410a5fe3ed6cc03f0f318af142202fd868787d83e5efa77d6211554
```

Ingrese esta clave en cabal para unirse al chat.

Cabal es súper joven, y aunque se está tratando de someterlo a prueba a medida que se desarrolla, a veces las cosas se rompen. Si es así, te pedimos seas paciente por favor y esperes que se repare.

Una vez que solicite su JWTOKEN, lo recibirá mediante [Wormhole](https://wormhole.app/).

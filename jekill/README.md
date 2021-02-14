# Blog.Github (En Español)
¿Cómo crear un blog por GitHub (Jekill)? - Traducido al español del repositorio de Jekill

# Jekyll

**Jekyll** es un generador de páginas Web que le brinda a GiyHub la manera de poder crear un blog ([Repositorio de Jekyll](https://github.com/jekyll/jekyll)); tu podrás crear tu landing page de forma gratuita con un repositorio de GitHub, sin pagar un hosting.

- No necesitas mucho código (Ni siquiera ser un programador)
- Es fácil de configurar y podrás borrar todo si no te gusta y volver a empezar desde cero.
- Puedes mostrar un portafolio sencillo en pocos minutos (con el creador de site de Jekill).

## ¡Comencemos!

### 1.- Hazle Fork a este repositorio

Dale Fork y renombralo con (tu_nombre_de_usuario).github.io.

Puedes ver tu blog después de realizar este procedimiento como <https://tu_nombre_de_usuario.github.io>

### 2.- Personaliza tu Sitio

Cambia el nombre, la descriptión, el avatar y cualquier otra opción con tan solo editar el archivo en el directorio raiz del repositorio llamado "_config.yml". puedes también activar conectarlo con Google Analytics y también agregar links e íconos de redes sociales.

Cambiar el archivo "_config.yml" (o cualquier archivo en tu nuevo repositorio) obligará a GitHub Pages a reconstruir tu sitio con Jekill. Tu sitio reconstruido será visible en uno o dos minutos por <https://tu_nombre_de_usuario.github.io> (A veces se tarda un poco más).

> Hay 3 formas diferentes de que puedas realizar cambios en los archivos de tu blog:
> 1.- Editando los archivos dentro de tu nuevo repositorio " tu_nombre_de_usuario.github.io " en el navegador de GitHub (mostrado abajo).
> 2.- Puedes usar un editor de contenido como [Prose by Development Seed](http://prose.io). Optimizado para usarlo con Jekill haciendo edición de marcado, escribir borradores, cabeceras y agregando imÁgenes de forma sencilla.
> 3. Clonar tu repositorio y hacer las actualización de forma local, luego hacerle "push" a tu repositorio de GitHub.
![_config.yml](/images/config.png "_config.yml")

### 3.- Publica tu Primer Post

Edita el archivo `/_posts/2020-08-01-hello-world.md` para publicar tu primer post. Esta [Hoja de Estilo de Marcado](http://www.jekyllnow.com/Markdown-Style-Guide/) puede ayudarte en algo.

![Primero Post](/images/first-post.png "First Post")

> ¡Puedes agregar post adicionales en el browser en GitHub.com también!! Solo pulsa el ícono de + en la carpeta`/_posts/` para crear nuevo contenido. Solo asegúrate de incluir [front-matter](http://jekyllrb.com/docs/frontmatter/) como bloque al inicio de cada post nuevo y asegurate que el archivo tenga este formato: año-mes-dia-título.md

## Desarrollo Local

1. Instala Jekill y sus plugins en una sola ronda. `gem install github-pages`; esto crea una copia exacta de los plugins usados por GitHub Pages en tu computador, incluyendo Jekill, Sass, etc.
2. Clona to Fork con`git clone https://github.com/yourusername/yourusername.github.io.git`
3. Haz "serve" al site y busca los cambios de marcado/sass `jekyll serve`
4. chequea tu website por http://127.0.0.1:4000/
5. Haz "commit" a cualquier cambio y "push" a todo para mandarlo a la rama "Master" de tu repositorio de GitHub. GitHub Pages reconstruira y lanzará tu sitio Web.

## Características Nuevas de Jekyll

✓ Línea de comando _fork-first workflow_, usando GitHub para crear, personalizar y postear a tu blog
✓ Temas totalmente responsivos y optimizados para mobile (**[Tema Demo](http://jekyllnow.com)**)  
✓ Soporta Sass/Coffeescript al usar Jekyll 2.0  
✓ Hosting gratuito en tu sitio de usuario de GitHub Pages
✓ Markdown blogging  
✓ Syntax highlighting  
✓ Integración de Google Analytics
✓ SVG íconos de RRSS en tu footer
✓ 3 request de http, incluyendo tu avatar

✘ No existen dependencias de instalación
✘ No necesitas de configurar un desarrollo local
✘ Sin configurar plugins
✘ No necesitas gastar tiempo (ni dinero) en temas
✘ Más tiempo para echar código en otras cosas... oh, espera ✓!  

## Preguntas?
[Abre un Issue](https://github.com/barryclark/jekyll-now/issues/new) y chateamos (En inglés)!

## Otros Temas "Forkeables"
Puedes usar un [Inicio Rápido](https://github.com/barryclark/jekyll-now#quick-start) con otros temas que se han configurados para ser "Forkeados"! aquí están algunos de mis favoritos:

- [Hyde](https://github.com/poole/hyde) por MDO
- [Lanyon](https://github.com/poole/lanyon) por MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) por Tom Preston-Werner
- [Left](https://github.com/holman/left) por Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) por Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) por Michael Rose

## Créditos
- [Jekyll](https://github.com/jekyll/jekyll) - Gracias a tus creadores, contribuidores y patrocinantes.
- [SVG icons](https://github.com/neilorangepeel/Free-Social-Icons) - Gracias, Neil Orange Peel, son excelentes todos.
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Gracias, Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Excelente artículos sobre Jekil. He usado el "feed.xml" de Joel en este repositorio.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Gracias por los reviews en el diseño/código.
- [Bart Kiers](https://github.com/bkiers), [Florian Simon](https://github.com/vermluh), [Henry Stanley](https://github.com/henryaj), [Hun Jae Lee](https://github.com/hunjaelee), [Javier Cejudo](https://github.com/javiercejudo), [Peter Etelej](https://github.com/etelej), [Ben Abbott](https://github.com/jaminscript), [Ray Nicholus](https://github.com/rnicholus), [Erin Grand](https://github.com/eringrand), [Léo Colombaro](https://github.com/LeoColomb), [Dean Attali](https://github.com/daattali), [Clayton Errington](https://github.com/cjerrington), [Colton Fitzgerald](https://github.com/coltonfitzgerald), [Trace Mayer](https://github.com/sunnankar) - ¡Gracias por las[contribuciones extraordinarias](https://github.com/barryclark/jekyll-now/commits/master) para el proyecto!

## Contribuciones
"Issues" y "Pull Requests" serán apreciadas. Si jamás has contribuido en un proyecto Open Source anteriormente, estaré más que agradecido y feliz de llevarte a crear un pull request.

Puedes comenzar con [abrir un  issue](https://github.com/barryclark/jekyll-now/issues/new), describir el problema que estás tratando de resolver e iremos desde ahí a resolverlo.

Quiero mantener a Jekill Now lo más minimalista posible. Cada línea de código debe algo que sea utilizable en un 90% para la gente que lo usa. Por favor, ten en mente que cuando ...........submitting feature requests. Si eso no es algo que mucha gente lo use, probablemente no le hagan "merged". :guardsman:

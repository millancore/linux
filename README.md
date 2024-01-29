
# Linux Setup

En la búsqueda de las herramientas mas efectivas y minimalistas para mi entorno de trabajo he creado este repositorio donde dejo notas y algunas configuraciones, no pretendo explicar el uso extenso de cada una, mas bien un resumen de sus características mas relevantes, dejo los enlaces oficiales para quien desee profundizar. 

- SO: **Manjaro** (Arch based)
Lo que mas destaca de las distribuciones  basadas en Arch es la calidad de documentación, si bien Arch tiene fama de ser difícil cuenta con varias distribuciones que son muy amigables a usuarios que no quieren llevar la experiencia Linux al extremo.

  https://manjaro-sway.download
  
- Gestor de Ventanas: **Sway**
Uso un solo monitor **wide** y lo mejor para este tipo de monitores ese un gestor de ventanas de tipo mosaico ya que me permite tener varias aplicaciones una al lado de la otra, la otra gran característica es que se maneja todo con el teclado y es altamente personalizable, lo único que me faltaba era un cambiar de ancho automático en la ventana  actual de esa manera poder tener N aplicaciones en un mismo espacio de trabajo pero lo he solucionado creando un script para ello.

  https://swaywm.org/

- Terminal
     - Emulador: **Wezterm**
       Hay muchos emuladores de terminal que me agradan, e elegido este porque su configuración es en Lua, (lenguaje que también uso para configurar NeoVim)   es rápido y
       tiene soporte para pestañas.
       
       https://wezfurlong.org/wezterm/index.html

     - Explorador de Archivos: **Yazi**
       Un explorador de archivos en la terminal muy sencillo con una filosofía Vim, con una previsualización muy buena y con una configuración muy simple, podes agregar             diferentes reglas para abrir distinto tipos de archivos.

       https://yazi-rs.github.io/
  
     - Buscador: **Fzf**
       Una de las herramientas mas poderosas y útiles que uso a diario, fzf es un listador que te permite filtrar en tiempo real todo tipo de listados, su uso es ilimitado y        muy sencillo.

       https://github.com/junegunn/fzf

     - Jumper: **Z**
       Navegar con `cd` en es muy lento y es aquí donde entra Z,  va creando un histórico de los directorios que visitas y la próxima vez es solo usar z para saltar al directorio usa el nombre `z <dirname>`

       https://github.com/rupa/z
       
     - Multipanel: **Tmux**
       Permite dividir la terminal para ejecutar diferentes comandos en cada una de las divisiones,  si usas un gestor de ventanas tipo baldosas no hay mucha diferencia pero con `tmuxinator` puedes crear archivos de proyecto para definir que se abre en cada panel y tamaño y posición lo que lo hace un herramienta  maravillosa. 
       
       https://github.com/tmux/tmux/wiki
       
       https://github.com/tmuxinator/tmuxinator 
       
- Editor:
    - **Neovim**
      https://neovim.io/
      
    - **PHPStorm**
      https://www.jetbrains.com/phpstorm
      - IdeaVim
        https://lp.jetbrains.com/ideavim/

        
      
- Laucher: **Rofi**
  https://github.com/davatorium/rofi

  
      
- Navegador: **Vivaldi**
    https://vivaldi.com/
  
  - **Vimium C**
    https://github.com/gdh1995/vimium-c




- Lenguajes
    - **Bash**
      https://tldp.org/LDP/Bash-Beginners-Guide/html/
      
    - **Lua**
      https://www.lua.org/manual/5.4/
      
    - **Rust**
      https://www.rust-lang.org/learn


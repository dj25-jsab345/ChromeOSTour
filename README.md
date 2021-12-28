# #ChromeOSTour, el proyecto de instalaciones de Chrome OS en PC's Windows

Aquí empieza el repositorio oficial de GitHub del proyecto #ChromeOSTour, el proyecto de instalaciones de Chrome OS desarrollado, empezado y llevado a cabo desde la comunidad de Mazthertutoriales.

## Comenzando 🚀

Si llegaste hasta aquí, es porque de manera directa o indirecta estás interesado en el #ChromeOSTour, y por tanto en instalar Chrome OS en tu PC Windows. ¡Me alegro que tengas interés! Empezaré por explicarte de qué trata el proyecto. El #ChromeOSTour, tal como su nombre lo indica, es un tour de Chrome OS (no me digas XD). No, pero hablando en serio, esta idea surge de algo que un noticiero en particular hace aquí en Colombia, que con un bus recorren casi todo el país y recolectan noticias e investigaciones. Algo similar ocurre en el caso del #ChromeOSTour, es un recorrido que da inicio en los DM de cada usuario perteneciente a la comunidad de Mazthertutoriales en Discord y Telegram, donde yo (o cualquiera de las manos ayudantes del proyecto) les ofrezco u ofrecen a cada usuario una instalación guiada del sistema operativo Chrome OS, con soporte y solución de problemas casi que 24/7.

## ¿Qué es Chrome OS?

Seguro te debes estar preguntando: ¿qué rayos es Chrome OS? Pues:

Chrome OS es un sistema operativo diseñado por Google basado en el kernel de Linux, diseñado específicamente para las PC portátiles conocidas con el nombre de Chromebooks. 

Ojo, es muy importante que no confundas, Chrome OS no es basado en Android x86; como el mismo fue creado por Google, ellos mismos le han aplicado el Framework de Android, así que por lo tanto no puede estar basado en ese SO.

Está programado en C# y C++, y aparte de ser un SO de escritorio gracias al kernel de Linux, es un sistema híbrido con Android, porque sí, con Chrome OS tienes la increíble pero a la vez no tan demasiadamente atractiva posibilidad de ejecutar LAS APPS DE ANDROID en una PC, sin requerir de un teléfono Android, ni de emuladores ni del complicado lío del Subsistema de Windows para Android (WSA/SWA) en Windows 11.

Como ya debes saber por su nombre, Chrome OS usa el navegador Google Chrome como su principal UI (Interfaz de Usuario), lo que significa que prácticamente el 50% de lo que hagas en Chrome OS será desde Google Chrome, un 20% desde Google Play, otro 20% con el Google Assistant y el 10% final con la app Archivos de Chrome OS. 

Chrome OS es un sistema operativo que funciona desde la nube, por lo tanto el espacio que ocupa directamente es casi de cero (bueno, no tanto así, porque si revisas la partición de Chrome OS (si instalas por dual-boot) en Windows, puedes ver que sí ocupa su buen espacio, pero cuando uses Chrome OS no se notará); el único espacio en tu disco que ocupa son las apps que descargues de la Play Store, las características que agregues y los datos de las apps; nada más.

### Ventajas ✅
Ahora puedes decir: ok, sí, ya conozco Chrome OS, pero ¿de qué me serviría tenerlo? (A veces de manera tosca) Pues, míralo por ti mismo:
- Puedes instalar y correr las apps de Android en la PC, ya que la Play Store viene de manera nativa.
- No requieres ni de emuladores, ni de sistemas basados en Android x86, ni de un teléfono Android, ni del COMPLICADO lío del Subsistema de Windows para Android (WSA/SWA) de Windows 11.
- Puedes gozar de un sistema ligero (bueno, no tanto así, porque si lo ves desde W11, claramente ves que no es tan ligero, pero si usas Chrome OS no lo notarás)
- No tienes necesidad de preocuparte por los virus; gracias a que la protección AV está integrada y sumándole la protección AV avanzada de Google Chrome, los virus poco pueden permitirse entrar en Chrome OS.
- Olvídate de los largos y eternos arranques; Chrome OS se inicia en tan sólo 30-45 segundos.
- Es un SO rápido; por su ligereza, sencillez y poca saturación de contenidos con respecto a otros SO, es considerablemente más optimizado y rápido, así que puedes usarlo para revivir PC's antiguas (no tan demasiado antiguas).
- (Por mis métodos) Tiene 3 diversos métodos de instalación, así que puedes elegir el que más te convenga para instalarlo o probarlo.

### Desventajas ❌
Acá viene lo no tan dulce y feliz; estos aspectos desagradables a muchos los puede hacer abandonar el tour.
- No es tan sencillo de instalar como CloudReady o Chromium OS; tienes que pasar por un proceso un tanto extenso y descargar archivos algo pesados para poder generar una IMG de Chrome OS arrancable con la que puedas arrancar. También requiere que sepas un poco de Linux.
- Es un poco exigente en requisitos; no es TAN exigente en requisitos como Windows 11, pero tampoco es omni-compatible (compatible con absolutamente todas las PC).
- NO SE RECOMIENDA EN LO ABSOLUTO que lo prueben las personas que se sientan DEMASIADO arraigadas o cómodas con Windows, puesto que Chrome OS se convertirá en un terreno demasiado nuevo para ellos.
- No es muy atractivo; es poco conocido.
- Tiene algunas características comunes de Windows eliminadas, tales como la de reiniciar directamente la PC.

Analiza estos aspectos y decide si potencialmente Chrome OS podría ser para ti.

## Métodos de instalación 🔧

Son 3, escoge el que más te convenga:

## MÉTODO 1: INSTALACIÓN POR EL MÉTODO DE USO DE DISCO COMPLETO
Consiste, básicamente, en instalar Chrome OS en tu PC usando toda la capacidad de tu disco duro, con los pasos que explicaré más adelante. Este método es recomendadísimo si eres de los usuarios que no te importaría borrar Windows, o si simplemente quieres revivir una PC antigua y dejarle nada más como SO principal Chrome OS.

## MÉTODO 2: INSTALACIÓN POR EL MÉTODO DEL DUAL-BOOT
Este consiste en, básicamente, si tu disco está en su capacidad completa (osea, no tiene ninguna partción), particionar tu disco duro en 2 partes para, desde el entorno de Linux Mint, instalar Chrome OS en esa partición (si ya está particionado y hay espacio suficiente, aún se puede crear una, y si tienes un disco duro externo, se instala ahí). Luego se configura un boot-loader (cargador de arranque) con un código generado en Linux Mint, para que cada que arranques tu PC, puedas elegir si bootear o arrancar con Chrome OS, o arrancar con Windows. Este método está más que recomendado para la gente que quiere conservar aún Windows en su disco duro, pero aún así quieren probar Chrome OS, o los (las) que ya están listos (as) para probarlo, y no requieren de un Live CD para probarlo, puesto que ya lo quieren probar directamente en el PC.

## MÉTODO 3: PRUEBA DEL SO POR EL MÉTODO DEL MODO LIVE CD
Este método es especialmente para aquellos (as) Mazthers y usuarios (as) precavidos (as) que prefieren probarlo en su PC sin tocar el disco completo, para que si no les gusta o no quedan satisfechos, no realicen ningún cambio indeseado en el PC y se les estropee algo. Este método tiene mucho en común con el primero, a excepción de que una vez tengas el pendrive con Chrome OS, lo que harás simplemente será arrancar el PC desde él y esperar a que cargue Chrome OS. Si eres uno (a) de esos (as) Mazthers, te doy una advertencia, para que no te lleves una sorpresa indeseada probando Chrome OS con este método: tus datos y aplicaciones no se conservarán con este método, puesto que al ser un Live CD, se comporta igual que cualquier Live CD de cualquier distro Linux: una vez apagues o reinicies, tus datos se eliminarán, a no ser que lo instales directamente en el disco.

## Instalando Chrome OS (Chrome OS Initial Flight) 🚀
Ya decidiste que Chrome OS era para ti? ¡Perfecto! Espero este repo te sirva de utilidad.

## Checando la compatibilidad ✅/❌
Antes de empezar, debes checar si la PC es compatible con Chrome OS. Para esto, llena este formulario, y con la información que recolecte (un resumen), deberás compararla con los requisitos de abajo:

https://docs.google.com/forms/d/e/1FAIpQLSflO4o9EnhbsCFLYCvky07HBAJgWpizXJlTaYtfkI-Y-4jUEw/viewform

## Requisitos de Chrome OS (desde el repo oficial de GitHub de Brunch Framework)

Son estos:

## Tipo de BIOS (desde el repo oficial de GitHub de Brunch Framework)

Debe ser de tipo UEFI, sin embargo, si es de tipo Heredada (BIOS/CSM/Legacy), aún se puede instalar, mediante el parche para BIOS/CSM/Legacy.

## Tipo de CPU (desde el repo oficial de GitHub de Brunch Framework)
Deben ser de la siguiente manera:

## Para las CPU Intel
- Si es Intel Core i3, i5 e i7, deben ser de la arquitectura/plataforma Sandy Bridge en adelante (2° generación en adelante)
- Si es Intel Core i3, i5 e i7 de 1° generación, será soportado hasta la versión 81 de Chrome OS (Chrome OS v81)
- Si es Intel Atom, Celeron o Pentium, debe ser de la plataforma/arquitectura Baytrail en adelante (2° generación en adelante)

## Para las CPU AMD
Estas tienen soporte limitado; pero si tu CPU AMD se encuentra dentro de estos parámetros, tienes vía libre para instalar o probar Chrome OS. 

- Si es AMD de las plataformas Stoney Ridge o Bristol Ridge, es soportado
- Si es AMD Ryzen, es soportado

## Esquema de particionamiento del disco duro (deducido por mí)
Para los que practicarán el método #2, deben tener el disco duro particionado como GPT, así el programa que se mencionará más adelante podrá encontrar fácilmente la partición de sistema EFI de Windows.

## Tipo de GPU o tarjeta gráfica (CRÍTICO) (desde el repo oficial de GitHub de Brunch Framework)
Este aspecto muchas veces determina si la PC es compatible.

- Si tienes una tarjeta gráfica de la marca NVIDIA **NO DESMONTABLE** (ej. laptop), inmediatamente tendrás luz roja para Chrome OS, porque las NVIDIA no son soportadas por Chrome OS.
- Si tienes una tarjeta gráfica de la marca NVIDIA **DESMONTABLE** (ej. PC's de sobremesa), desmóntala y deja que el PC coexista con sus gráficos integrados para poder probar Chrome OS.
- Si tienes una tarjeta gráfica de marcas diferentes a NVIDIA (ej. MSI o ASRock), puedes instalar Chrome OS en ese PC.
- Y si no tienes ninguna tarjeta gráfica externa, puedes instalar Chrome OS.

## Capacidad de la USB de destino (fuentes mixtas)
Si intentarás el método #1 o #3, deberás tener una USB de mínimo 16 GB. Si intentarás el método #2, debes tener una de mínimo 4 GB.

Compara tus resultados con estos requisitos.

## Descargando los archivos necesarios ⬇️

En la página **Releases**, encontrarás el entorno configurado para Chrome OS, según tu tipo de CPU, BIOS y versión de Chrome OS.
Ve al Release que sea de acuerdo a tu tipo de PC y versión de Chrome OS.
Un ejemplo:
```
Si la PC es Intel de 3° generación, de BIOS UEFI e instalarás por disco completo, escoge el release que contenga estos datos.
```
Encontrarás en tu release 2 archivos ZIP comprimidos, uno que contiene tu recovery de Chrome OS y la herramienta Brunch Framework descomprimidos en la misma carpeta, y el otro contiene alguno que otro insumo necesario para tu tipo de instalación. Descarga los 2 ZIP, y descomprime SÓLO el zip, no la carpeta dentro de él, y mueve la carpeta del primer ZIP a tu carpeta raíz del sistema, si instalarás por el método #2, así la localizarás fácilmente.

## Instalando Chrome OS (método #1 para BIOS UEFI) 🔧
Una vez tengas tus archivos guardados y descomprimidos, abre el instalador del Oracle VM VirtualBox y sigue sus pasos atentamente. Si te pide instalar un controlador, dale a Sí. Cuando se instale, crea una VM (das a Nuevo) y ponle estas configuraciones:
- Nombre: Linux Mint 20.2 Uma (Cinnamon Edition)
- Tipo de SO: Linux
- Versión: Other Linux (la arquitectura de la CPU)
- RAM: Si tienes 4 de RAM, asígnale 1 GB; si tienes 8, asígnale 2; y si tiene 16; asígnale 4.

Y en la parte del disco, dale a Abrir un archivo de disco virtual existente. Dale a la carpeta amarilla con la flecha verde hacia abajo y en la ventana que se te abra, localiza el .vdi de Linux Mint (viene en el 2° zip) y dale a Abrir.
Dale a Aceptar e inicia la VM.

Una vez la VM haya iniciado, te pedirá contraseña de usuario; la contraseña es **osboxes.org** (la misma tanto para iniciar sesión como para activar el usuario root).

Una vez estés en el escritorio, tendrás que instalar las VirtualBox Guest Additions para poder compartir la carpeta resultante del 1° ZIP a la VM y de allí generar la IMG de Chrome OS. Para eso, ve a Dispositivos > Insertar imagen de CD de las "Guest Additions".

Una vez haya sido insertada, te pedirá si deseas ejecutar los medios. Dale a Sí y deja que se ejecuten. Si te pide confirmaciones en la Terminal, pon Y y dale a Enter. Cuando te salga "Press Return to close this window" presiona Enter.

Abre otra Terminal desde la barra de tareas y ejecuta este comando:

```
sudo adduser osboxes vboxsf
```
Pon la contraseña de usuario root y da Enter. Cuando finalice, cierra la Terminal y apaga la VM.

Lo siguiente sería configurar la carpeta compartida; para eso tendrás que cliquear la VM que creaste y darle a Configuración. Luego ve al apartado de Carpetas compartidas, y localiza la carpeta azul con la flecha verde de la parte superior derecha. Hazle clic. 

En Ruta de carpeta, abre el menú desplegable y selecciona Otro... . 
Navega hasta la ruta donde tienes alojada la carpeta que compartiremos con la VM para crear la IMG de Chrome OS, selecciónala y dale a Abrir.

Marca la casilla de Automontar y dale a Aceptar u Ok.
Cierra la ventana de Configuración e inicia la VM, dando en Iniciar, y mete todo lo que tengas que meter mientras arranca.

Una vez en el escritorio, verás que se te ha creado un atajo llamado "sf_(nombre de la carpeta compartida)", donde lo que está dentro de los paréntesis es el nombre de la carpeta compartida, que usualmente suele ser ChromeOS o Chrome OS. Ábrelo.

Haz clic derecho en una zona vacía de la ventana y dale a "Open in Terminal".

Allí, introduce los siguientes comandos UNO por UNO, seguidos de la tecla Enter.

1. Para asignarte los privilegios de usuario root:

```
sudo su
```
2. Para actualizar los repositorios y dependencias de la VM de Linux Mint:
```
sudo apt-get update
```
O alternativamente,
```
apt-get update
```
3. Para instalar la dependencia cgpt, necesaria para Chrome OS
```
sudo apt-get install cgpt
```
O alternativamente,
```
apt-get install cgpt
```
4. Para instalar la dependencia pv, necesaria para Chrome OS:
```
sudo apt-get install pv
```
O alternativamente,
```
apt-get install pv
```
5. Para generar la imagen de Chrome OS:
```
sudo bash chromeos-install.sh -src (nombre completo y exacto del archivo del recovery) -dst chromeos.img
```
O alternativamente,
```
bash chromeos-install.sh -src (nombre completo y exacto del archivo del recovery) -dst chromeos.img
```

Ahora te toca esperar un buen rato, puesto que la IMG pesa 14 GB.

Cuando esté instalado, te dirá "ChromeOS installed." 

Cuando suceda esto, verás en la carpeta en Windows la IMG creada. Ahora puedes proceder a cerrar todo en la VM y apagarla. Ahora lo que harás será abrir Rufus e insertar tu USB de mínimo 16 GB. 
Toma en cuenta estas configuraciones:

- Si tu BIOS es de tipo UEFI, en esquema de partición, selecciona GPT.
- Si tu BIOS es de tipo Heredada (BIOS/CSM/Legacy), selecciona MBR.

Luego dale a Empezar y deja que termine.

Cuando lo haga, reinicia la PC y arranca desde esa USB. Como es el primer arranque, suele tardar bastante, así que sé paciente.
Cuando te salga el logo de Chrome en la pantalla, espera unos segundos hasta que estés en el OOBE (Out-of-Box Experience, Experiencia fuera de caja o configuraciones iniciales). 
Cuando lo estés, complétalas hasta donde te salga la opción de Navegar como invitado. Dale ahí y se te abrirá una ventana de Chrome.

Luego presiona la combinación de teclas Ctrl + Alt + T, y se te abrirá el crosh, la terminal para desarrolladores de Chrome OS. Desde ahí instalaremos Chrome OS.

Ahora pon ahí estos comandos UNO por UNO, seguido de la tecla Enter:

1. Para abrir el shell de Chrome OS:
```
shell
```
2. Para identificar tu disco principal (guíate por su capacidad)
```
sudo fdisk -l (L)
```
3. Para seleccionar el disco en el crosh, y trabajar con él usando el fdisk:
```
sudo fdisk /dev/sdX/
```
Donde X es la letra que Chrome OS le asignó al disco.

3.1 Pon esta letra y pulsa Enter tantas veces como particiones tenga tu disco
```
d 
```
3.2 Pon esta letra y da a Enter 3 veces:
```
n
```
3.3 Pon estas letras UNA por UNA seguidas de la tecla Enter:
```
p
```
,
```
w
```
3.4 Pon este comando seguido de la tecla Enter:
```
sudo fdisk -l (L)
```
4. Para instalar Chrome OS:
```
sudo chromeos-install -dst /dev/sdX 
```
(Donde X es la letra nueva que Chrome OS le asigna al disco, si no le asigna nueva, la misma de los anteriores pasos)

Ahora a esperar.

Si todo va bien, verás al final "ChromeOS installed."
Ya lo único que tienes que hacer será apagar la PC, retirar la USB, encenderla de nuevo y dejar que arranque el SO.

## Instalando Chrome OS (método #1, BIOS heredada (BIOS/CSM/Legacy))
Los pasos para instalarlo son los mismos que para UEFI, sólo que en tu carpeta de Chrome OS estará el parche para BIOS/Legacy agregado, y tus pantallas de arranque serán diferentes.

## Instalando Chrome OS (método #2, BIOS UEFI)
Revisa mi canal de YT, ahí estará el tutorial guiado. 
https://www.youtube.com/watch?v=3LbwVJlSRUA (Pt.1)
https://www.youtube.com/watch?v=a-UW50_qjpM&t=376s (Pt.2)

## Instalando Chrome OS (método #2, BIOS heredada (BIOS/CSM/Legacy))
No puedes; dado que este proceso no genera el código para poner en el Grub2Win, para probarlo tienes que usar el método #3.

## Instalando Chrome OS (método #3, BIOS UEFI)
Sigue los pasos para el método #1 y BIOS UEFI **HASTA** la parte donde flasheas la IMG en la USB. A partir de aquí lo único que te toca hacer será arrancar la PC desde la USB, dejar que arranque por primera vez y completar la configuración inicial (OOBE).

## Instalando Chrome OS (método #3, BIOS heredada (BIOS/CSM/Legacy))
Sigue los mismos métodos del apartado anterior.

Si completaste los pasos correspondientes a tu método satisfactoriamente, ...

**¡¡¡ FELICIDADES !!!**

Lograste instalar y probar Chrome OS con éxito. ¡Disfrútalo!

Si tienes reportes de errores, ve al apartado **Issues**

Si tienes FAQ's, ve al apartado **Wiki**

¡Espero que hayas disfrutado de participar en el proyecto!

#ChromeOSTour

Proyecto dirigido por DJ25_JSAB345

Apoyado por la comunidad de Mazthertutoriales

Hecho con mucho esfuerzo 💪 y 💓 por DJ25_JSAB345 [https://github.com/dj25-jsab345]

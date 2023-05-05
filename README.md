### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA POR TERMUX 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/shorts/PESW8LXXlOI?feature=share)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/The-DiosBot-MD/The-ParaguyBot-MD/master/gata.sh | bash
```
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/GataNina-Li/GataBot-MD/master/gata.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/[rama]/gata.sh | bash"
```
#### MODIFICAR ARCHIVO [`para.sh`](https://github.com/GataNina-Li/GataBot-MD/blob/master/gata.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/GataNina-Li/GataBot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd GataBot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```
-----
### 🪄 (OPCIÓN 2) INSTALACIÓN MANUAL POR TERMUX - GITHUB 
> **Note** Comandos para instalar de forma manual
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install git nodejs ffmpeg imagemagick yarn && git clone https://github.com/-Li/The-DiosBot-MD && cd The-ParaguyBot-MD && yarn install && npm install && npm start
```
> **Warning** Si aparece (Y/I/N/O/D/Z) [default=N] ? use la letra "y" + "ENTER" para continuar con la instalación 
------------------
### 📁 (OPCIÓN 3) INSTALACIÓN POR TERMUX - ARCHIVOS
> **Note** Descargué y Descomprime
### [`The-ParaguyBot-MD ~ Archivos`](https://github.com/The-ParaguyBot-MD/The-ParaguyBot-MD/archive/refs/heads/master.zip)
[![blog](https://img.shields.io/badge/Termux-The-ParaguyBot-MD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/UcWlyQ8u5HE)
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
cd storage/downloads/The-ParaguyBot-MD-master/The-ParaguyBot-MD-master 
yarn install
npm install
npm start
```
* #### APLICACIÓN RECOMENDADA PARA [`DESCOMPRIMIR`](https://play.google.com/store/apps/details?id=com.rarlab.rar)
* #### APLICACIÓN RECOMENDADA PARA EDITAR [`NÚMERO DE OWNER`](https://play.google.com/store/apps/details?id=com.rhmsoft.code)
> **Note** Guardar los archivos en la ubicación: storage/downloads/The-ParaguyBot-MD-master/The-ParaguyBot-MD-master   
----
### 🚀 USAR THE-PARAGUYBOT-MD 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta The-ParaguyBot-MD
```bash
termux-wake-lock && npm i -g pm2 && pm2 start index.js && pm2 save && pm2 logs 
``` 
#### ⬇️ Opciones Disponibles
> **Warning** Esto eliminará todo el historial que hayas establecido con PM2:
```bash 
pm2 delete index
``` 
> Si tienes cerrado Termux y quiere ver de nuevo la ejecución use:
```bash 
pm2 logs 
``` 
> Si desea detener la ejecución de Termux use:
```bash 
pm2 stop index
``` 
> Si desea iniciar de nuevo la ejecución de Termux use:
```bash 
pm2 start index
``` 
----
###  ACTUALIZAR PARABOT
> **Note** Comandos para actualizar ParaBot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/The-DiosBot-MD/The-ParaguyBot-MD/master/update.sh | bash 
```
#### Para que no pierda su progreso en ParaBot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                           
----
### 🟣 ACTIVAR EN HEROKU 
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/The-DiosBot-MD/The-ParaguyBotMD-Heroku) 
### 👇 Añada lo siguente al Buildpack: 
```bash
heroku/nodejs
```
```bash
https://github.com/jonathanong/heroku-buildpack-ffmpeg-latest.git
```
```bash
https://github.com/clhuang/heroku-buildpack-webp-binaries.git
```
-----
- [x] Resultado <details><summary>Buildpack</summary><img src="https://i.imgur.com/t3Xzgnh.jpeg"></details>
-----

### ✅ BOXMINEHOST 
[![blog](https://img.shields.io/badge/BoxMine/The-DiosBot-MD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/Ko019wvu2Tc)
> Activar GataBot-MD 24/7 en BoxMine Host

<a href="https://boxmineworld.com"><img src="https://i.imgur.com/allAyd4.png" height="125px"></a>
### BoxMine World

- Pagina Oficial: [`https://boxmineworld.com`](https://boxmineworld.com)
- Tutorial - Crea una cuenta en la Dashboard: [`https://www.youtube.com/watch?v=ZAwBLuNmIlI`](https://www.youtube.com/watch?v=ZAwBLuNmIlI)
- Dashboard: [`https://dash.boxmineworld.com`](https://dash.boxmineworld.com)
- Panel: [`https://panel.boxmineworld.com`](https://panel.boxmineworld.com)
- Dudas UNICAMENTE SOBRE EL HOST: [`https://discord.gg/84qsr4v`](https://discord.gg/84qsr4v) (Preguntar por Vicemi)

- [x] Resultado <details><summary>Ajustes del Servidor - ParaBot-MD</summary><img src="https://i.imgur.com/N0SwvbY.jpeg"></details>
------------------
### ⚡ REPLIT - PARABOT
[![blog](https://img.shields.io/badge/Replit-GataBotMD-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://youtu.be/pQYkq4xv37o)
<a target="_blank" href="https://replit.com/github/The-DiosBot-MD/The-ParaguyBot-MD"><img alt="Run on Replit" src="https://binbashbanana.github.io/deploy-buttons/buttons/remade/replit.svg"></a>
<a href="https://replit.com/github/The-DiosBot-MD/The-ParaguyBot-MD"> <img src="https://media0.giphy.com/media/lMwu8EJAnv9kmn51KQ/giphy.gif" height="29px"></a>
------------------
- [x] Resultado <details><summary>Importar Repositorio - ParaBot-MD</summary><img src="https://i.imgur.com/GQyRnMf.jpg"></details>
------------------
### 🌱 ACTIVAR EN KOYEB 

[![Deploy to Koyeb](https://www.koyeb.com/static/images/deploy/button.svg)](https://app.koyeb.com/deploy?type=git&repository=github.com/The-DiosBot-MD/The-ParaguyBot-MD&branch=master&name=Parabot-md)

------------------
### ☁️ ACTIVAR EN RENDER 
[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://dashboard.render.com/blueprint/new?repo=https%3A%2F%2Fgithub.com%2FThe-DiosBot-MD%2FParaBot-MD) 

------------------
## 💻 PARA USUARIOS DE WINDOWS/VPS/RDP

* Descargar e instala Git [`Aquí`](https://git-scm.com/downloads)
* Descargar e instala NodeJS [`Aquí`](https://nodejs.org/en/download)
* Descargar e instala FFmpeg [`Aquí`](https://ffmpeg.org/download.html) (**No olvide agregar FFmpeg a la variable de entorno PATH**)
* Descargar e instala ImageMagick [`Aquí`](https://imagemagick.org/script/download.php)
* Descargar e instala Yarn [`Aquí`](https://classic.yarnpkg.com/en/docs/install#windows-stable)
```bash
git clone https://github.com/GataNina-Li/GataBot-MD && cd GataBot-MD && npm install && npm update && node .
```
## 💻 Instalación de FFmpeg para Windows 
* Descarga cualquiera de las versiones de FFmpeg disponibles haciendo clic en [FFmpeg](https://www.gyan.dev/ffmpeg/builds/).
* Extraer archivos a `C:\` path.
* Cambie el nombre de la carpeta extraída a `ffmpeg`.
* Ejecute el símbolo del sistema como administrador.
* Ejecute el siguiente comando:
```cmd
> setx /m PATH "C:\ffmpeg\bin;%PATH%"
```
Si tiene éxito, le dará un mensaje como: `SUCCESS: specified value was saved`.
* Ahora que tiene FFmpeg instalado, verifique que funcionó ejecutando este comando para ver la versión:
```cmd
> ffmpeg -version
```
---- PREGUNTAS.... 

<details>
<summary><b>Preguntas sobre BoxMine</b></summary>

- [x] **¿Cómo puedo crear una cuenta en BoxMine?**<br>
_Puede ver esa información [`Aquí 👈`](https://github.com/The-DiosBot-MD/The-ParaguyBot-MD/#-boxminehost)_

- [x] **¿Cómo puedo actualizar?**<br>
_Detener el servidor con el botón `STOP` luego ir a la pestaña `FILES` y descargar el archivo `database.json` dicho archivo es donde se almacena el progreso del Bot, luego de hacer el respaldo debe de eliminar todos los archivos y carpetas de `FILES`, luego ir a la pestaña `SETTINGS` y usar el Botón `REINSTALL SERVER` después espera un momento y cuando aparezca información del servidor ir a la pestaña `FILES` para agregar el archivo `database.json` que respaldó, luego guardar los cambios ir a la pestaña `CONSOLE` y usar el Botón `RESTART`. De ese modo se actualizará el Bot (Cabe recalcar que se borrará las configuraciones que hizo en `config.js` por lo que si quiere volver agregar la información deberá de editar dicho archivo antes de usar `RESTART`)._

- [x] **¿Cómo puedo obtener un nuevo código QR?**<br>
_Use el botón `STOP` luego ir a la pestaña `FILES` y borrar la carpeta `ParaBotSession` guarde los cambios y luego ir a la pestaña `CONSOLE` y tendrá un nuevo código QR de debe de escanear._

- [x] _Si tiene más dudas puede decirlo por el [`🟣 Servidor de Discord`](https://discord.gg/84qsr4v)_
</details>

----
### SOBRE PARABOT ~ GB-GLOBAL
<details>
<summary><b>Objetivo</b></summary><br>

  - [x] _Proporcionar un Bot funcional para WhatsApp que ofrezca una amplia gama de funciones, compatibilidad con múltiples idiomas, automatización y una alta eficiencia en su desempeño._
  - [x] _El Bot estaría diseñado para brindar una experiencia de usuario intuitiva y accesible, permitiendo a los usuarios realizar diversas tareas sin la necesidad de salir de la aplicación de WhatsApp._
  - [x] _Proporcionar una herramienta que sea útil para una amplia audiencia, al mismo tiempo que ofrezca una solución efectiva y sencilla para las necesidades cotidianas en el uso de WhatsApp._

</details>

<details>
<summary><b>Funcionamiento</b></summary><br>

  - [x] _ParaBot utiliza la utilidad de Javascript y Shell para crear un código altamente funcional que permite gestionar la compatibilidad con WhatsApp._
  - [x] _Con el uso de la biblioteca de código abierto Baileys, GataBot establece una conexión directa con la aplicación de WhatsApp, lo que permite una experiencia de usuario fluida._
  - [x] _Se utiliza fuentes externas, APIs, imágenes, videos y documentos en línea para proporcionar una herramienta auténtica y completa que solventa una amplia gama de necesidades dentro de WhatsApp. Con estas características, los usuarios pueden disfrutar de una experiencia de usuario mejorada y eficiente al utilizar ParaBot._

</details>

<details>
<summary><b>Privacidad</b></summary><br>

  - [x] _En GataBot, la seguridad y privacidad de los usuarios son una prioridad fundamental. El código del Bot está diseñado para ser seguro tanto para el propietario del Bot como para los usuarios que interactúan con él._
  - [x] _En lo que respecta a la recopilación de datos, GataBot solo recopila información pública, como el nombre de usuario, la descripción y la foto de perfil, con el único propósito de mantener el progreso del usuario en el Bot o identificar valores necesarios para realizar las funciones del Bot._
  - [x] _El código de GataBot es completamente público y puede ser revisado detalladamente sin ningún inconveniente. Con estas características, los usuarios pueden estar seguros de que su información y privacidad están protegidas al interactuar con ParaBot._

</details>

<details>
<summary><b>Edición & Material</b></summary><br>

  - [x] _ParaBot está diseñado para ser altamente personalizable, por lo que si tienes conocimientos previos de código, puedes realizar modificaciones libremente en el código del Bot. Sin embargo, aunque el código es público y editable, por favor no olvides mencionar los créditos correspondientes para que ParaBot siga recibiendo más novedades y mejoras en el futuro._
  - [x] _La personalización del Bot puede hacerse tanto a nivel de código como a través de herramientas de configuración, dependiendo de la plataforma o framework que se esté utilizando._  
  - [x] _En cuanto al material que contiene GataBot, los usuarios pueden esperar encontrar una amplia variedad de contenido, incluyendo memes, inteligencia artificial que depende del PROMPT que reciba, contenido para adultos (quedando en el juicio del usuario asumir si tiene la edad suficiente para comprender dicho contenido), información que cambia dependiendo de la solicitud del usuario, audios y stickers. Por favor, ten en cuenta que nos reservamos el derecho de juzgar dicho contenido y tomar las medidas necesarias para mantener un ambiente seguro y apropiado en el uso de GataBot._

</details>

<details>
<summary><b>Términos de uso</b></summary><br>

  - [x] _Es importante mencionar que el uso del Bot es bajo la responsabilidad del usuario, y que el propietario del Bot no se hace responsable del uso indebido que se pueda hacer de él._
  - [x] _Es recomendable establecer restricciones claras sobre el tipo de uso que se puede hacer del Bot._
  - [x] _Es importante mencionar que el Bot no está diseñado para cometer spam, phishing u otros tipos de actividades maliciosas, y que su uso con estos fines está prohibido._

</details>

<details>
<summary><b>Recomendaciones</b></summary><br>

  - [x] _Es importante mencionar que se recomienda tener una buena conexión a Internet, no solo para una experiencia de usuario más fluida, sino también para garantizar un correcto funcionamiento del Bot._
  - [x] _Es recomendable tener suficiente espacio de almacenamiento libre para el Bot, ya que esto puede afectar su capacidad para procesar y almacenar datos. Tener una memoria RAM mínima de 3 GB, ya que esto puede ayudar a garantizar una experiencia de usuario fluida y evitar que el Bot se bloquee o se ralentice._
  - [x] _Es importante mencionar que se recomienda usar el WhatsApp Messenger para el Bot, ya que esto puede garantizar una mayor flexibilidad en cuanto a la compatibilidad con diferentes dispositivos y sistemas operativos._
  - [x] _Es recomendable tener en cuenta que el Bot puede funcionar de manera estable en un máximo de 30 grupos considerando las características anteriores._
  - [x] _Es importante mencionar que el Bot funciona aún si el WhatsApp no tiene Internet._
  - [x] _Si encuentra alguna falla de visibilidad de mensajes, se recomienda volver a escanear el código QR para garantizar una conexión correcta entre el Bot y el WhatsApp._

</details>

<details>
<summary><b>Actualizaciones y cambios</b></summary><br>

  - [x] _ParaBot está en constante evolución y mejora, cada actualización busca solucionar errores, mejorar la eficiencia de las funciones existentes, agregar nuevas funciones y optimizar los recursos para una experiencia más fluida. Le recomendamos que se mantenga actualizado con las últimas versiones para disfrutar de todas las mejoras y nuevas características que se implementen en el futuro. ¡Gracias por usar ParaBot!_

</details>

----
### 💠 [`IDIOMAS DISPONIBLES PARA PARABOT`](https://github.com/The-DiosBot-MD/The-ParaguyBot-MD/blob/master/config.js) 
#### 🌐 Español  
#### 🌐 Inglés (English) 
#### 🌐 Portugués (Português)
#### 🌐 Indonesio (Bahasa Indonesia) 
#### 🌐 Árabe (عرب)
- [x] Ejemplo <details><summary>Idioma</summary><img src="https://i.imgur.com/RMWFgZo.jpeg"></details>
----

### 🌟 CREADOR 
[![GataNina-Li](https://github.com/The-DiosBot-MD.png?size=100)](https://github.com/The-DiosBot-MD) 

### 🌟 AGRADECIMIENTOS
[![TheShadowBrokers1](https://github.com/BrunoSobrino.png?size=60)](https://github.com/BrunoSobrino) 

# Bee-Bot-MD
> <b>🚀 VERSIÓN 1.4.0</b>

<p align="center"> 
<a href="https://github.com/GataNina-Li"><img src="http://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=A1F733&width=435&lines=𝖡𝗋𝗈𝗅𝗒-Bot-MD;Disfruta+del+bot.+%E2%9A%A1" height="90px"></a> 
</p>

<p align="center">
<img src="https://telegra.ph/file/697daa9b111db9ff4c45e.jpg" alt="GataBot-MD" width="900"/>
</p>

<p align="center">
<a href="#"><img title="Bee-Bot-MD" src="https://img.shields.io/badge/SI TE AGRADA EL REPOSITORIO APÓYAME CON UNA 🌟 ¡GRACIAS! -red?colorA=%255ff0000&colorB=%23017e40&style=for-the-badge"></a>
</p>  

<p align="center">
<a href="#"><img title="Bee-Bot-MD" src="https://img.shields.io/badge/COMPATIBLE CON LA VERSIÓN MULTI DISPOSITIVOS DE WHATSAPP-red?colorA=%F77F48FF&colorB=%F77F48FF&style=for-the-badge"></a>
</p>

<p align="center">   
<a href="https://github.com/Kronoscorporation/Bee-Bot-MD/network/members"><img title="Forks" src="https://img.shields.io/github/forks/KronosCorporation/Bee-Bot-MD?label=Forks&color=blue&style=flat-square"></a>
<a href="https://github.com/KronosCorporation/Bee-Bot-MD/watchers"><img title="Watchers" src="https://img.shields.io/github/watchers/Kronoscorporation/Bee-Bot?label=Watchers&color=green&style=flat-square"></a>
<a href="https://github.com/KronosCorporation/Bee-Bot-MD/stargazers"><img title="Stars" src="https://img.shields.io/github/stars/KronosCorporation/Bee-Bot-MD?label=Stars&color=yellow&style=flat-square"></a>
</p>

### Cuentas Oficiales:
> Al acceder a la plataforma, obtendrás acceso a todos los enlaces oficiales de KronosCorporation. Además, te mantendremos informado con boletines y mensajes exclusivos sobre las últimas novedades. La página se actualiza constantemente para ofrecerte la información más relevante. ¡No te pierdas ninguna actualización y únete a nuestro canal ahora mismo!

<a href="https://instabio.cc/BeeUwU">
<img src="https://img.shields.io/badge/Redes_Sociales-000000%7D?style=for-the-badge&logo=biolink&logoColor=white">
</a>

-----
### 🌟 (OPCIÓN 1) INSTALACIÓN AUTOMÁTICA POR TERMUX 🫰
[![blog](https://img.shields.io/badge/Instalacion-Automatica-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/shorts/ZLJYDUM6vSY)
> **Note** Comandos para instalar de forma automática en Termux  
```bash
termux-setup-storage
```
```bash
apt update -y && yes | apt upgrade && pkg install -y bash wget mpv && wget -O - https://raw.githubusercontent.com/KronosCorporation/Bee-Bot-MD/master/Bee.sh | bash
```
```js
// PERSONALIZAR INSTALACIÓN AUTOMÁTICA (En caso de una Bifurcación)
// Parámetros editables

// REFERENCIA
"wget -O - https://raw.githubusercontent.com/KronosCorporation/Bee-Bot-MD/master/Bee.sh | bash"

// PARÁMETROS QUE PUEDE SER MODIFICADOS --> "[...]"
"wget -O - https://raw.githubusercontent.com/[usuario]/[repositorio]/[rama]/Bee.sh | bash"
```
#### MODIFICAR ARCHIVO [`Bee.sh`](https://github.com/KronosCorporation/Bee-Bot-MD/blob/master/Bee.sh)
```js
//LÍNEAS A MODIFICAR
205 --> "git clone https://github.com/[user]/[repositorio].git"
//Ejemplo: git clone https://github.com/KronosCorporation/Bee-Bot-MD.git

209 --> "cd [repositorio]"
//Ejemplo: cd Bee-Bot-MD

//Una vez hecho estos cambios ejecute los nuevos comandos en Termux
```
-----
### 🪄 (OPCIÓN 2) INSTALACIÓN MANUAL POR TERMUX - GITHUB 
> **Note** Comandos para instalar de forma manual
```bash
termux-setup-storage
```
```bash
apt update && apt upgrade && pkg install git nodejs ffmpeg imagemagick yarn && git clone https://github.com/KronosCorporation/Bee-Bot-MD && cd Bee-Bot-MD && yarn install && npm install && npm start
```
> **Warning** Si aparece (Y/I/N/O/D/Z) [default=N] ? use la letra "y" + "ENTER" para continuar con la instalación 
------------------
### 📁 (OPCIÓN 3) INSTALACIÓN POR TERMUX - ARCHIVOS
> **Note** Descargué y Descomprime
### [`Bee-Bot-MD ~ Archivos`](https://github.com/KronosCorporation/Bee-Bot-MD/archive/refs/heads/master.zip)
[![blog](https://img.shields.io/badge/NO_TUTORIAL-FF0000?style=for-the-badge&logo=youtube&logoColor=white)
](https://www.youtube.com/shorts/ZLJYDUM6vSY)
```bash
termux-setup-storage
apt update
apt upgrade
pkg install -y git nodejs ffmpeg imagemagick yarn
cd storage/downloads/Bee-Bot-MD-master/Bee-Bot-MD-master 
yarn install
npm install
npm start
```
* #### APLICACIÓN RECOMENDADA PARA [`DESCOMPRIMIR`](https://play.google.com/store/apps/details?id=com.rarlab.rar)
* #### APLICACIÓN RECOMENDADA PARA EDITAR [`NÚMERO DE OWNER`](https://play.google.com/store/apps/details?id=com.rhmsoft.code)
> **Note** Guardar los archivos en la ubicación: storage/downloads/Bee-Bot-MD-master/Bee-Bot-MD-master   
----
### 🚀 USAR BEEBOT 24/7 EN TERMUX 
> Ejecutar estos comandos dentro de la carpeta Bee-Bot-MD
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
### 🥷🏻 ACTUALIZAR BEEBOT
> **Note** Comandos para actualizar Bee-Bot-MD de forma automática
```bash
grep -q 'bash\|wget' <(dpkg -l) || apt install -y bash wget && wget -O - https://raw.githubusercontent.com/KronosCorporation/Bee-Bot-MD/master/update.sh | bash 
```
#### Para que no pierda su progreso en Broly-Bot, estos comandos realizarán un respaldo de su `database.json` y se agregará a la versión más reciente.
> **Warning** Estos comandos solo funcionan para TERMUX, REPLIT, LINUX                           
----

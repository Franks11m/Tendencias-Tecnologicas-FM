# Práctica: Instalación y configuración de un proyecto Angular con comandos Linux

## 1. Título  
**Proyecto Angular con Linux**

## 2. Tiempo de duración  
**150 minutos**

## 3. Fundamentos

En esta práctica se abordó el desarrollo de una aplicación Angular desde un entorno Linux, específicamente utilizando Ubuntu como sistema operativo base. Angular es un framework de desarrollo web creado por Google que permite construir aplicaciones dinámicas de una sola página (SPA - Single Page Application) utilizando TypeScript, HTML y CSS.

Para el desarrollo en Angular se requiere un entorno configurado con Node.js, npm (Node Package Manager), y Angular CLI (Command Line Interface). Linux ofrece un entorno versátil y muy poderoso para este tipo de desarrollos, ya que mediante comandos en la terminal es posible instalar, configurar y ejecutar herramientas sin necesidad de interfaces gráficas.

Durante la práctica se aprendió a:
- Utilizar comandos de Linux para moverse entre carpetas, crear directorios y editar archivos.
- Instalar Angular CLI mediante `npm`.
- Crear un nuevo proyecto Angular desde cero con el comando `ng new`.
- Ejecutar el servidor de desarrollo con `ng serve` para ver los cambios en tiempo real desde el navegador.
- Solucionar errores comunes como problemas con permisos (`sudo`), falta de `package.json`, o errores en la instalación de dependencias.

El uso de imágenes en esta parte del informe ayudará a comprender mejor la estructura de carpetas de un proyecto Angular, la interfaz de la terminal y el resultado final en el navegador.
> **Figura 1-1.** Logotipo de Angular.
 <img src="photos/1_1HXCJCOpzKdmQI33ZrEIlg.png" alt="drawing" width="500"/>


## 4. Conocimientos previos

Para desarrollar correctamente esta práctica, se requiere que el estudiante tenga conocimiento de:

- Comandos básicos de Linux.
- Navegación de archivos desde terminal.
- Uso de navegadores web.
- Instalación de herramientas desde consola (npm, Angular CLI).
- Instalacion de paquetes de manera manual.


## 5. Objetivos a alcanzar

- Configurar un entorno de desarrollo web sobre Linux.
- Ejecutar y comprobar un servidor Angular desde terminal.
- Manipular archivos de configuración dentro de un proyecto Angular.


## 6. Equipo necesario

- Computador con sistema operativo Windows, Linux o macOS.
- Ubuntu instalado (en máquina real, virtual o WSL).
- Terminal Bash.
- Node.js v18 o superior.
- Angular CLI (última versión estable).
- Navegador actualizado (Chrome, Firefox, etc.).

---

## 7. Material de apoyo

- [Documentación de Angular](https://angular.io/)
- [Documentación de WSL](https://learn.microsoft.com/en-us/windows/wsl/)
- Guía de comandos básicos de Linux.
- Guía video colocado en la plataforma virtual del Instituto https://drive.google.com/file/d/1OitqZ02pX7VHaVx3qH9eF31mQent65rk/view
- Cheatsheet de comandos de Linux.

---

## 8. Procedimiento

**Paso 1:** Instalar WSL y Ubuntu dentro del terminal de PowerShell
```bash
wsl --install -d Ubuntu
```

> **Figura 8-1-1.** Instalación de Ubuntu.
 <img src="photos/Captura de pantalla 2025-04-03 160647.png" alt="drawing" width="600"/>
 
> **Figura 8-1-2.** Instalación wsl.
 <img src="photos/Captura de pantalla 2025-04-04 155905.png" alt="drawing" width="600"/>


**Paso 2:** Abrir Ubuntu e instalar Node.js y npm si no están instalados.  
```bash
sudo apt update
sudo apt install nodejs npm
```
> **Figura 8-2-1.** Estructura básica de un proyecto Angular.
 <img src="photos/Captura de pantalla 2025-04-04 150416.png" alt="drawing" width="600"/>
 
> **Figura 8-2-2.** Estructura básica de un proyecto Angular.
 <img src="photos/Captura de pantalla 2025-04-04 150430.png" alt="drawing" width="600"/>


**Paso 3:** Instalar Angular CLI.
```bash
npm install -g @angular/cli
```
> **Figura 8-3-1.** Instalar Angular CLI globalmente..
 <img src="photos/Captura de pantalla 2025-04-04 150632.png" alt="drawing" width="600"/>
 
> **Figura 8-3-2.** Se cargan los recursos nesesarios.
 <img src="photos/Captura de pantalla 2025-04-04 150702.png" alt="drawing" width="600"/>
 
> **Figura 8-3-3.** Obtenemos Angular CLI ultima versión.
 <img src="photos/Captura de pantalla 2025-04-04 150822.png" alt="drawing" width="600"/>
 
**Paso 4:** Crear un nuevo proyecto Angular.
```bash
mkdir linux-franks
ng new "nombre-del-proyecto" en mi caso lo llame "y"
```
> **Figura 8-3-1.** Creamos carpeta de proyectos.
 <img src="photos/Captura de pantalla 2025-04-04 151005.png" alt="drawing" width="600"/>
 
> **Figura 8-3-2.** Creamos un proyecto Angular dentro de ese directorio.
 <img src="photos/Captura de pantalla 2025-04-04 151025.png" alt="drawing" width="600"/>
 
> **Figura 8-3-3.** Instalacion de recursos nesesarios del proyecto.
 <img src="photos/Captura de pantalla 2025-04-04 151119.png" alt="drawing" width="600"/>

**Paso 5:** Iniciar el servidor de desarrollo.  
```bash
ng serve
```
> **Figura 8-5-1.** Instalacion de recursos nesesarios del proyecto.
 <img src="photos/Captura de pantalla 2025-04-04 153237.png" alt="drawing" width="800"/>

**Paso 6:**  Abrir el navegador y acceder a http://localhost:4200 para ver la app funcionando. 


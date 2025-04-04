# Práctica: Servidor Web

## 1. Título  
**Proyecto Angular con Linux**

---

## 2. Tiempo de duración  
**150 minutos de sufrimiento técnico y aprendizaje 💻🔥**

---

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

> **Figura 1-1.** Estructura básica de un proyecto Angular.  
> ![Estructura Angular](https://angular.io/generated/images/marketing/conceptual-architecture.png)

> **Figura 1-2.** Comandos de instalación y ejecución desde Ubuntu.  
> ![Terminal Ubuntu](https://i.imgur.com/5uRJ7Ux.png)

---

## 4. Conocimientos previos

Para desarrollar correctamente esta práctica, se requiere que el estudiante tenga conocimiento de:

- Comandos básicos de Linux.
- Navegación de archivos desde terminal.
- Uso de navegadores web.
- Fundamentos de desarrollo frontend (HTML, CSS, JavaScript/TypeScript).
- Instalación de herramientas desde consola (npm, Angular CLI).

---

## 5. Objetivos a alcanzar

- Implementar contenedores web utilizando Angular.
- Configurar un entorno de desarrollo web sobre Linux.
- Ejecutar y comprobar un servidor Angular desde terminal.
- Manipular archivos de configuración dentro de un proyecto Angular.
- Usar herramientas como Docker para despliegue futuro (en caso de extender la práctica).

---

## 6. Equipo necesario

- Computador con sistema operativo Windows, Linux o macOS.
- Ubuntu instalado (en máquina real, virtual o WSL).
- Terminal Bash.
- Cuenta en DockerHub o Docker Play (opcional para despliegue).
- Docker v20.10 o superior (opcional).
- Node.js v18 o superior.
- Angular CLI (última versión estable).
- Navegador actualizado (Chrome, Firefox, etc.).

---

## 7. Material de apoyo

- Documentación oficial de Angular: [https://angular.io/docs](https://angular.io/docs)
- Guía de la asignatura.
- Cheatsheet de comandos de Linux.
- StackOverflow y foros de programación.
- Documentación oficial de Docker (opcional).

---

## 8. Procedimiento

**Paso 1:** Abrir Ubuntu e instalar Node.js y npm si no están instalados.  
```bash
sudo apt update
sudo apt install nodejs npm

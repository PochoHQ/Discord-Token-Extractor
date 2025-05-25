# ⭐ Discord Token Extractor / Extractor de Token de Discord ⭐

> A simple, lightweight script to effortlessly retrieve and copy your Discord token with styled console output.  
> Un script simple y ligero para obtener y copiar fácilmente tu token de Discord con salida estilizada en la consola.

---

## 🚀 What it does / ¿Qué hace?

This script automatically finds and displays your **Discord token** directly in your browser console with a colorful and neat design.  
Además, incluye una función para copiar el token al portapapeles con un solo comando.

Ideal for developers, power users, and anyone needing quick access to their token for debugging, automation, or personal development.  
Ideal para desarrolladores, usuarios avanzados y cualquiera que necesite acceso rápido a su token para debugging, automatización o desarrollo personal.

---

## 🎯 Features / Funcionalidades

- Automatic token detection through Discord’s internal webpack structure.  
- Salida en consola estilizada:  
  - *Pocho.dev* en rojo y tamaño pequeño.  
  - Token en blanco con fondo negro y fuente grande para facilitar la lectura.  
- Global function `copyToken()` to copy the token to your clipboard with a single command.  
- Función global `copyToken()` para copiar el token al portapapeles con un solo comando.  
- Compatible with modern browsers (Chrome, Firefox) supporting the `copy()` function in console.  
- Código fácil de usar y modificar.

---

## ⚙️ How to use / Cómo usar




![imagen](https://github.com/user-attachments/assets/5b9def6f-28cf-4926-aabd-5c611659bc1e)


1. Open Discord in your browser (or web app).  
   Abre Discord en tu navegador (o la app web).
2. Open Developer Tools (press `F12` or `Ctrl + Shift + I` / `Cmd + Option + I`).  
   Abre las herramientas de desarrollador (`F12` o `Ctrl + Shift + I` / `Cmd + Option + I`).
3. Go to the **Console** tab.  
   Ve a la pestaña **Consola**.
4. Paste the script code (normal or minified) into the console and press Enter.  
   Pega el código del script (normal o minificado) en la consola y presiona Enter.
5. You’ll see your token displayed with style.  
   Verás tu token mostrado con estilo.
6. To copy the token to your clipboard, simply execute:  
   Para copiar el token al portapapeles, ejecuta:  
   ```js
   copyToken();

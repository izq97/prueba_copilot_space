# 🚀 Documentación de GitHub Copilot

## 📌 ¿Qué es Copilot?
[GitHub Copilot](https://github.com/features/copilot) es una herramienta de inteligencia artificial desarrollada por GitHub y OpenAI que ayuda a los desarrolladores a escribir código más rápido y con menos esfuerzo.  
Funciona como un "pair programmer" que sugiere líneas completas de código, funciones o incluso tests en tiempo real.

---

## ⚙️ Instalación

### 1. Requisitos previos
- Tener una cuenta de **GitHub** con suscripción a Copilot.
- Visual Studio Code (VS Code) o un IDE compatible.
- Extensión de GitHub Copilot instalada.

### 2. Instalación en VS Code
1. Abre **VS Code**.
2. Ve a `Extensiones (Ctrl+Shift+X)`.
3. Busca **GitHub Copilot** e instálala.
4. Inicia sesión con tu cuenta de GitHub.
5. Activa tu suscripción de Copilot.

---

## ✨ Uso básico

1. Abre un archivo de código (por ejemplo, `app.js`).
2. Empieza a escribir una función o comentario descriptivo.
3. Copilot sugerirá automáticamente código en gris.
4. Pulsa `Tab` para aceptar la sugerencia o `Esc` para descartarla.

---

## 💡 Ejemplo práctico

```javascript
// Calcula la suma de un array de números
function sumArray(numbers) {
    return numbers.reduce((acc, num) => acc + num, 0);
}

# 🎓 Portal Web de la EICA

![Estado: Activo](https://img.shields.io/badge/Estado-Activo-blue)
![Contribuciones: Bienvenidas](https://img.shields.io/badge/Contribuciones-Bienvenidas-brightgreen)

¡Bienvenido/a al repositorio oficial de la página web de la **Escuela de Ingeniería y Ciencias Aplicadas (EICA)** de la **Universidad de Oriente (UDO), Núcleo Monagas, Venezuela**! Este proyecto de código abierto tiene como propósito ser el rostro digital de la escuela, ofreciendo información relevante para estudiantes, profesores y el público en general.

## 🚀 Tecnologías Utilizadas

- **[React](https://reactjs.org/)** (Librería UI)
- **[TypeScript](https://www.typescriptlang.org/)** (Tipado estático)
- **[Vite](https://vitejs.dev/)** (Herramienta de compilación web)
- **[Tailwind CSS](https://tailwindcss.com/)** (Framework CSS)

## 🛠️ Requisitos Previos

Antes de comenzar a contribuir, asegúrate de tener instalado:

- **[Git](https://git-scm.com/downloads)** (Para control de versiones)
- **[Node.js](https://nodejs.org/)** (Entorno de ejecución)
- Un editor de código de tu preferencia, recomendamos **[VS Code](https://code.visualstudio.com/)**

## ⚙️ Instalación y Desarrollo Local

Para correr este proyecto en tu entorno local, sigue los siguientes pasos:

1. **Clona tu repositorio** (preferiblemente de tu Fork, ver sección de Contribuciones abajo):
   ```bash
   git clone https://github.com/TU_USUARIO/eicaenlinea.git
   cd eicaenlinea
   ```

2. **Instala las dependencias**:
   Para descargar todas las librerías necesarias del proyecto ejecuta:
   ```bash
   npm install
   ```

3. **Inicia el servidor de desarrollo**:
   Levanta el proyecto localmente con el siguiente comando:
   ```bash
   npm run dev
   ```
   Esto iniciará Vite y usualmente podrás ver la página abriendo tu navegador en `http://localhost:5173/`. ¡Cualquier cambio que guardes en el código se reflejará instantáneamente gracias al Hot Module Replacement (HMR)!

---

## 🤝 Cómo Contribuir al Proyecto

¡Nos encanta recibir contribuciones de la comunidad estudiantil y desarrolladores externos! Para agregar nuevas funcionalidades, corregir errores o mejorar la documentación, sigue estos pasos:

### 1. Haz un "Fork" del repositorio
Un *Fork* es una copia de este proyecto en tu propia cuenta de GitHub, lo que te permite hacer cambios libremente sin afectar la página en vivo de la escuela.

- Ve a la esquina superior derecha de esta página y haz clic en el botón **Fork**.

### 2. Clona el repositorio a tu computadora
Una vez que tengas el fork en tu cuenta, debes descargarlo a tu equipo local.

```bash
# Cambia "TU_USUARIO" por tu nombre de usuario de GitHub
git clone https://github.com/TU_USUARIO/eicaenlinea.git

# Entra a la carpeta del proyecto
cd eicaenlinea
```

### 3. Configura el repositorio original (Upstream)
Para asegurarte de que tu código siempre esté actualizado con los cambios oficiales de la escuela, añade este repositorio como "upstream".

```bash
# Añade el enlace original del repositorio de la organización (EICA-UDO-Monagas)
git remote add upstream https://github.com/EICA-UDO-Monagas/eicaenlinea.git
```

### 4. Crea una nueva rama (Branch)
**Nunca** hagas cambios directamente en la rama principal (`main` o `master`). Crea una rama con un nombre descriptivo para tu trabajo.

```bash
git checkout -b mi-nueva-caracteristica
# Ejemplo: git checkout -b mejorar-cabecera
```

### 5. Realiza tus cambios y guárdalos (Commit)
Trabaja en el código. Cuando estés listo para guardar, agrega los archivos y haz un commit con un mensaje claro de lo que modificaste.

```bash
# Agregar todos los cambios
git add .

# Guardar los cambios con un mensaje
git commit -m "feat: actualización del banner de admisiones 2026"
```

### 6. Sincroniza con el proyecto original
Antes de enviar tu trabajo, asegúrate de traer cualquier cambio que otros hayan hecho mientras tú programabas.

```bash
git fetch upstream
git rebase upstream/main
```

### 7. Sube los cambios a tu GitHub (Push)
Envía la rama con tus modificaciones a tu cuenta de GitHub.

```bash
git push origin mi-nueva-caracteristica
```

### 8. Abre un Pull Request (PR)
1. Ve a tu repositorio en GitHub.
2. GitHub detectará tus cambios y mostrará un botón verde que dice **Compare & pull request** (Comparar y solicitar fusión). Haz clic ahí.
3. Explica detalladamente qué problemas resolviste o qué característica agregaste.
4. Envía el Pull Request y espera a que los mantenedores del proyecto revisen tu código. ¡Gracias por tu aporte! 🎉

---

## 🐛 Reportar Problemas (Issues)

Si encuentras un enlace roto, un error de diseño, o tienes una sugerencia, por favor abre un **Issue** en la pestaña correspondiente de GitHub. Asegúrate de incluir:
- Una descripción clara del problema.
- Pasos para reproducirlo.
- Capturas de pantalla (si aplica).

## 📄 Licencia

Este proyecto está distribuido bajo la licencia **Apache License 2.0**. Revisa el archivo `LICENSE` para más información.

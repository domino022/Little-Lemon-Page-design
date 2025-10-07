# 🧩 CHECKLIST DIARIO DE GIT — FLUJO DE TRABAJO LOCAL

📍 **Proyecto:** Little Lemon  
💻 **Entorno:** Visual Studio Code  
📦 **Repositorio local:** Inicializado con `git init`

---

## 🗓️ ANTES DE EMPEZAR TU SESIÓN

✅ 1️⃣ Abre Visual Studio Code  
✅ 2️⃣ Abre tu proyecto:  
✅ 3️⃣ Abre la terminal integrada (`Ctrl + \``)  
✅ 4️⃣ Verifica que estás dentro del proyecto:
```bash
pwd

✏️ MIENTRAS TRABAJAS

🔹 Modifica tus archivos (index.html, style.css, etc.)
🔹 Guarda los cambios con Ctrl + S
🔹 Prueba en el navegador con Live Server

| Paso   | Comando                                        | Propósito                                  |
| ------ | ---------------------------------------------- | ------------------------------------------ |
| 🧐 1️⃣ | `git status`                                   | Ver qué archivos cambiaron                 |
| ➕ 2️⃣  | `git add .`                                    | Añadir todos los cambios al “staging area” |
| 💬 3️⃣ | `git commit -m "Descripción clara del cambio"` | Guardar la nueva versión                   |
| 🔍 4️⃣ | `git log --oneline`                            | Ver historial de commits                   |
| 🧹 5️⃣ | *(opcional)* `git diff`                        | Ver detalles de los cambios                |

✨ EJEMPLOS DE COMMIT PROFESIONALES

✅ “Agrego estructura base HTML del sitio”
✅ “Estilos del header con Flexbox”
✅ “Sección hero responsive”
✅ “Animo botones con hover y transición”
✅ “Añado imágenes del menú y actualizo footer”

💡 Evita mensajes genéricos como “arreglo cosas” o “update”.

| Momento           | Acción                     | Descripción                                  |
| ----------------- | -------------------------- | -------------------------------------------- |
| ☀️ Mañana         | `git status`               | Ver en qué estado dejaste el proyecto ayer   |
| 🧠 Durante el día | `git add .` + `git commit` | Guarda tus avances por secciones             |
| 🌙 Final del día  | `git log --oneline`        | Revisa tus commits y cierra el día tranquilo |

| Situación                   | Comando                  | Qué hace                                |
| --------------------------- | ------------------------ | --------------------------------------- |
| Ver historial resumido      | `git log --oneline`      | Muestra commits en una línea            |
| Ver diferencias             | `git diff`               | Muestra líneas cambiadas                |
| Ver configuración           | `git config --list`      | Muestra tu nombre y correo              |
| Salir del modo `(END)`      | `q`                      | Cierra el visor de texto en la terminal |
| Quitar archivos del staging | `git restore --staged .` | Saca los archivos del área temporal     |

CONSEJO PROFESIONAL

Haz un commit por cada tarea o sección terminada.
Así puedes retroceder exactamente hasta el punto que quieras si algo falla.

Ejemplo:

🧱 Estructura HTML completa → commit

🎨 Estilos del header → commit

📱 Diseño responsive → commit

🔒 EN RESUMEN: TU MANTRA DIARIO
git status
git add .
git commit -m "mensaje claro"


✨ Tres líneas, y todo tu progreso quedará guardado, protegido y organizado profesionalmente.

🚀 Autor

Luis Ruiz
Proyecto: Little Lemon — Curso Meta Front-End Developer

---



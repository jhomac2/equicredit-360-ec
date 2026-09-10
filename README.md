# 🇪🇨 EquiCredit 360 EC Pro — Evaluador de Riesgo Crediticio & Analytics de Buró (Ecuador)

**EquiCredit 360 EC Pro** es un simulador web interactivo y motor de análisis de riesgo crediticio desarrollado bajo la lógica y estándares del mercado ecuatoriano (Superintendencia de Bancos y Equifax Ecuador). Mide el Score Crediticio en una escala de **1 a 999 puntos**, calcula la capacidad de endeudamiento (DTI 30%), ofrece pre-aprobaciones crediticias y genera un **Informe de Crédito Premium** en PDF listo para imprimir.

---

## ☁️ Persistencia de Datos y Guardado Permanente (Opción 2: Google Sheets + LocalStorage)

Para evitar pérdidas de información si el usuario borra la caché o el historial de su navegador, **EquiCredit 360 EC Pro** implementa una arquitectura híbrida de almacenamiento seguro y gratuito:

### 1. 📊 Conexión con Google Sheets (Opción 2 - Recomendada para almacenamiento en la nube):
* **¿Cómo funciona?:** La app permite conectar de forma directa y gratuita una hoja de cálculo privada de **Google Sheets** del propio usuario mediante un script sencillo de **Google Apps Script**.
* **Paso a paso para configurar:**
  1. Abre tu Google Drive y crea una hoja de cálculo llamada `Mi_Buro_EquiCredit`.
  2. En la hoja, ve a **Extensiones** ➔ **Apps Script**.
  3. Pega el script de sincronización (incluido en la guía de la app) y presiona **Implementar** ➔ **Nueva implementación** ➔ **Aplicación web** (Acceso: *Cualquier persona*).
  4. Copia la URL del Web App resultante e ingrésala en la sección **"Configuración de Nube"** dentro de EquiCredit 360 EC Pro.
  5. ¡Listo! Cada evaluación o cambio se guardará automáticamente en tu Google Drive. Aunque borres el historial del navegador o cambies de dispositivo, tus datos permanecerán 100% seguros y respaldados.

### 2. 💻 Almacenamiento Local (`LocalStorage`):
* Si el usuario prefiere no usar Google Sheets, la aplicación guarda automáticamente los datos en la memoria interna de su navegador (`LocalStorage`). Los datos no viajan a servidores externos de terceros, garantizando privacidad absoluta.

### 3. 📥 Respaldo Manual en JSON:
* Incluye botones para **Descargar Copia de Seguridad (.json)** y **Restaurar Copia (.json)** con un solo clic.

---

## ✨ Características y Módulos Principales
* **📊 Score Crediticio (1 a 999 Puntos):** Tacómetro interactivo con animación y semáforo de riesgo neón (Alto, Medio, Bajo, Perfil AAA).
* **📈 Ratio de Endeudamiento (DTI 30%):** Evaluación del nivel de apalancamiento frente al límite máximo recomendado por la educación financiera ecuatoriana.
* **🏦 Pre-Aprobador de Créditos Ecuatorianos:** Simula la viabilidad de aprobación para Crédito Hipotecario (BIESS/Bancos), Automotriz, Tarjeta de Crédito y Microcréditos.
* **📄 Reporte Oficial Impreso / PDF:** Generación de un "Informe de Crédito Premium" con marca de agua, membrete institucional y sello de verificación digital (código QR / Hash).
* **📱 Interfaz Responsive & Mobile-First:** Diseñado para adaptarse perfectamente a smartphones y escritorios usando Tailwind CSS y Chart.js.
* **💡 Plan de Acción Personalizado:** Recomendaciones automáticas para incrementar el puntaje crediticio en periodos de 30, 60 y 90 días.

---

## 🛠️ Tecnologías Utilizadas
* **HTML5 & JavaScript Vanilla:** Lógica algorítmica de cálculo de score, integración con Google Apps Script y pre-aprobación crediticia.
* **Tailwind CSS (via CDN):** Diseño moderno estilo *Dark Neon & Glassmorphism*.
* **Chart.js:** Gráficos de gauge (tacómetro), donas y barras para visualización de riesgo.
* **Lucide Icons:** Iconografía limpia y profesional.
* **Google Apps Script / Google Sheets API:** Sincronización remota de datos en la nube del usuario.

---

## 👨‍💻 Creador & Contacto Directo

Desarrollado por **Jhordy** desde Pichincha, Ecuador 🇪🇨. Disponible para proyectos de desarrollo web, análisis de datos y desarrollo de software fintech.

* 📍 **Ubicación:** Tupigachi, Cantón Pedro Moncayo, Provincia de Pichincha — Ecuador 🇪🇨
* 📱 **WhatsApp / Teléfono:** [+593 963923399](https://wa.me/593963923399)
* 🎵 **TikTok:** [@I´m_Jhordy](https://www.tiktok.com/@I%CC%81m_Jhordy)
* 🐙 **GitHub:** [github.com/By_Jhordy](https://github.com/By_Jhordy)

---
*Proyecto libre desarrollado con fines educativos y de demostración de portafolio profesional en LinkedIn.*

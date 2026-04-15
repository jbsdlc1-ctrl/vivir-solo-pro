# Vivir Solo Pro 🏠🚀

**Vivir Solo Pro** es una aplicación web interactiva diseñada para acompañar a jóvenes en su transición hacia la independencia. Ofrece herramientas prácticas para organizar la mudanza, gestionar el presupuesto mensual y resolver dudas a través de un asistente con Inteligencia Artificial.

## ✨ Características Principales

- **Lista de Básicos por Departamentos**: Organiza lo que necesitas para tu nueva casa (Cocina, Limpieza, Baño, Habitación).
- **Gestor de Presupuesto**: Controla tus gastos mensuales con gráficos interactivos de distribución.
- **Asistente IA (Gemini)**: Un compañero digital disponible 24/7 para resolver dudas sobre contratos, limpieza, ahorro y más.
- **Consejos de Expertos**: Biblioteca de trucos y guías para ahorrar dinero y organizar el hogar.
- **Sistema de Planes Premium**: Acceso escalonado a funciones avanzadas mediante integración de pagos con PayPal.
- **Diseño Moderno y Responsivo**: Interfaz pulida, animada y optimizada para dispositivos móviles y escritorio.

## 🛠️ Tecnologías Utilizadas

- **React 18** + **TypeScript**
- **Vite** (Build tool)
- **Tailwind CSS** (Estilizado)
- **Framer Motion** (Animaciones)
- **Lucide React** (Iconografía)
- **Recharts** (Gráficos de datos)
- **Google Gemini API** (Inteligencia Artificial)

## 🚀 Instalación y Configuración Local

1. **Clonar el repositorio**:
   ```bash
   git clone https://github.com/tu-usuario/vivir-solo-pro.git
   cd vivir-solo-pro
   ```

2. **Instalar dependencias**:
   ```bash
   npm install
   ```

3. **Configurar variables de entorno**:
   Crea un archivo `.env` en la raíz del proyecto y añade tu clave de API de Gemini:
   ```env
   VITE_GEMINI_API_KEY=tu_clave_aqui
   ```

4. **Iniciar el servidor de desarrollo**:
   ```bash
   npm run dev
   ```

## 💳 Configuración de Pagos (PayPal)

La aplicación está configurada para recibir pagos directamente a través de PayPal. Para cambiar la cuenta de recepción, edita el archivo `src/App.tsx` y busca las referencias a `jbsdlc10@gmail.com`.

## 📄 Licencia

Este proyecto está bajo la Licencia Apache 2.0. Consulta el archivo `LICENSE` para más detalles.

---
*Desarrollado con ❤️ para ayudar a la próxima generación de independientes.*

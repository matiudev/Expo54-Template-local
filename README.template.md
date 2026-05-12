# 📱 NombreApp

> Descripción corta y directa de qué hace la app y para quién es.

---

## 📖 Descripción

Párrafo explicando el propósito principal de la app, el problema que resuelve y sus características más destacadas. Puede mencionar el modelo de datos clave o el enfoque técnico si es relevante.

---

## ✨ Características Principales

### 🏦 Característica 1
- Sub-característica A
- Sub-característica B
- Sub-característica C

### 💰 Característica 2
- Sub-característica A
- Sub-característica B
- Sub-característica C

### 🗂️ Característica 3
- Sub-característica A
- Sub-característica B
- Sub-característica C

### 📊 Característica 4
- Sub-característica A
- Sub-característica B
- Sub-característica C

### 🔐 Característica 5
- Sub-característica A
- Sub-característica B
- Sub-característica C

---

## 🛠️ Stack Tecnológico

| Categoría | Tecnología | Versión |
|-----------|-----------|---------|
| Framework | React Native + Expo | - |
| Backend / DB | Supabase | - |
| Estado Global | Zustand | - |
| Navegación | React Navigation | - |
| Estilos | NativeWind | - |

---

## 📁 Estructura del Proyecto

```
NombreApp/
├── src/
│   ├── components/        # Componentes globales reutilizables
│   ├── constants/         # Colores, íconos, constantes globales
│   ├── feature/           # Módulos por dominio (Feature-Based)
│   │   ├── auth/
│   │   ├── dashboard/
│   │   └── .../
│   ├── lib/               # Configuración de servicios externos (Supabase, etc.)
│   ├── navigation/        # Navegadores y stacks
│   ├── screens/           # Pantallas principales de los tabs
│   ├── theme/             # Contexto y definiciones de tema
│   └── utils/             # Funciones utilitarias
├── assets/                # Imágenes, íconos, splash screen
├── App.js
├── app.json
└── package.json
```

---

## 🧭 Navegación

```
RootNavigator
├── AuthStack (sin sesión)
│   ├── LoginScreen
│   └── RegisterScreen
│
└── AppStack (con sesión)
    ├── TabNavigator (bottom tabs)
    │   ├── 🏠 Tab 1
    │   ├── 📊 Tab 2
    │   └── 👤 Tab 3
    │
    └── Stack Screens
        ├── PantallaA
        ├── PantallaB
        └── PantallaC
```

---

## 🚀 Instalación y Configuración

### Prerrequisitos
- **Node.js** >= 18
- **Expo CLI**: `npm install -g expo-cli`
- **Expo Go** en tu teléfono o un simulador iOS/Android

### Pasos

```bash
# 1. Clonar el repositorio
git clone <repo-url>
cd NombreApp

# 2. Instalar dependencias
npm install

# 3. Configurar variables de entorno
cp .env.example .env

# 4. Iniciar el servidor de desarrollo
npx expo start
```

### Variables de Entorno

```env
EXPO_PUBLIC_SUPABASE_URL=https://tu-proyecto.supabase.co
EXPO_PUBLIC_SUPABASE_ANON_KEY=tu-anon-key
```

---

*Hecho con ❤️ por [matiudev](https://github.com/matiudev)*

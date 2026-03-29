# Ubienvivo - App de Ubicación en Tiempo Real

Aplicación Android que permite compartir tu ubicación en tiempo real de forma automática según horarios establecidos.

## 🎯 Características

- ✅ Compartir ubicación en tiempo real
- ✅ Visualizar ubicación de otros usuarios en OpenStreetMap
- ✅ Programar compartición por horarios y días específicos
- ✅ Sin necesidad de tarjeta de crédito
- ✅ Basado en tecnologías open source

## 🛠️ Tech Stack

- **Android & Kotlin**: Desarrollo nativo
- **Jetpack Compose**: UI moderna
- **OpenStreetMap + Osmdroid**: Mapas sin restricciones
- **Supabase**: Backend gratuito (PostgreSQL + Realtime)
- **Google Play Services**: Ubicación precisa
- **WorkManager**: Tareas automáticas programadas

## 📦 Requisitos

- Android Studio Flamingo o superior
- JDK 11 o superior
- Android SDK 24+
- Conexión a internet

## 🚀 Instalación

### 1. Clonar el repositorio
\`\`\`bash
git clone https://github.com/kevinbrittez-dev/ubienvivo.git
cd ubienvivo
\`\`\`

### 2. Abrir en Android Studio
- Abre Android Studio
- Selecciona "Open an Existing Project"
- Navega a la carpeta del proyecto

### 3. Sincronizar dependencias
```
File > Sync Now
```

### 4. Configurar Supabase (próximo paso)
- Crear cuenta en https://supabase.com
- Obtener URL y API Key
- Configurar en `app/src/main/java/com/kevinbrittez/ubienvivo/config/SupabaseConfig.kt`

## 📁 Estructura del Proyecto

```
ubienvivo/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/kevinbrittez/ubienvivo/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── services/
│   │   │   │   │   └── LocationService.kt
│   │   │   │   ├── ui/
│   │   │   │   │   ├── screens/
│   │   │   │   │   └── theme/
│   │   │   │   ├── data/
│   │   │   │   │   ├── repository/
│   │   │   │   │   └── models/
│   │   │   │   └── utils/
│   │   │   ├── res/
│   │   │   └── AndroidManifest.xml
│   │   └── test/
│   └── build.gradle.kts
├── settings.gradle.kts
└── README.md
```

## 📝 Próximos Pasos

- [ ] Configurar Supabase
- [ ] Implementar autenticación
- [ ] Crear servicio de ubicación
- [ ] Diseñar UI principal
- [ ] Integrar mapa OpenStreetMap
- [ ] Programación de horarios
- [ ] Sistema de amigos/contactos

## 📄 Licencia

MIT

---

**Hecho con ❤️ por kevinbrittez-dev**

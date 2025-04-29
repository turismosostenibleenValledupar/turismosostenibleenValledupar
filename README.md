# Aplicación Móvil AR para Turismo Sostenible en Valledupar

**Proyecto de Grado**  
Metodología CDIO | ODS #8 y #12  
Ciudad: Valledupar — "Capital Mundial del Vallenato"

---

## Descripción del Proyecto
Valledupar posee un rico patrimonio cultural y natural, pero enfrenta desafíos para impulsar un turismo sostenible y diversificado que beneficie a las comunidades locales y proteja su legado. Este proyecto propone desarrollar una aplicación móvil innovadora que promueva el turismo sostenible en Valledupar a través de tecnologías de Realidad Aumentada (AR).

La app ofrecerá:
- Información interactiva sobre atractivos turísticos (descripciones, imágenes, horarios, tarifas).  
- Mapas y rutas optimizadas.  
- Experiencias AR (reconstrucciones históricas, modelos 3D de objetos culturales).  
- Contenido dinámico proveniente de un backend (Firebase/API propia).

## Objetivos
- **CDIO**: Concebir, Diseñar, Implementar y Operar un prototipo TRL5.  
- **ODS #8**: Fomentar trabajo decente y crecimiento económico local.  
- **ODS #12**: Promover producción y consumo responsables en turismo.

## Características Principales
1. **HomeScreen**: Lista de atractivos con tarjetas detalladas.  
2. **MapScreen**: Visualización geolocalizada (react-native-maps + expo-location).  
3. **ARScreen**: Experiencia inmersiva de AR con ViroReact.  
4. **Backend**: Integración con Firebase para contenido dinámico.  
5. **Diseño UX/UI**: Interfaz intuitiva y accesible.

## Estructura de Carpetas
```
AR_Tourism_App/
├── README.md
├── app.json
├── package.json
├── babel.config.js
├── assets/
│   └── icon.png
├── src/
│   ├── App.js
│   ├── navigation/
│   │   └── AppNavigator.js
│   ├── screens/
│   │   ├── HomeScreen.js
│   │   ├── MapScreen.js
│   │   └── ARScreen.js
│   ├── components/
│   │   ├── AttractionCard.js
│   │   └── Header.js
│   └── ar/
│       └── InitialARScene.js
│   └── data/
│       └── attractions.js
└── .gitignore
``` 

## Tecnologías y Dependencias
- **Framework**: Expo + React Native  
- **Navegación**: React Navigation  
- **Mapas**: react-native-maps, expo-location  
- **AR**: ViroReact (ViroARSceneNavigator)  
- **Backend**: Firebase (Firestore / Storage) o API REST propia  

## Instalación y Ejecución
1. Clona el repositorio:  
   ```bash
git clone https://github.com/tu-usuario/AR_Tourism_App.git
cd AR_Tourism_App
```  
2. Instala dependencias:  
   ```bash
npm install # o yarn
```  
3. Inicia Expo:  
   ```bash
expo start
```  
4. Escanea el QR con tu dispositivo o emulador.

## Uso
- **Home**: Explora la lista de atractivos y filtra por categorías.  
- **Mapa**: Visualiza ubicaciones y obtén rutas optimizadas.  
- **AR**: Activa la cámara y descubre contenido 3D superpuesto en el entorno real.

## Fase Ingenieril y Gestión de Requerimientos
Durante esta fase, el equipo deberá:

- **Fortalecer la metodología CDIO**: Detallar cada etapa (Concebir, Diseñar, Implementar, Operar) con entregables claros.
- **Análisis de Requerimientos**: Recopilar, priorizar y documentar especificaciones funcionales y no funcionales de la app.
- **Nivel de Maduración Tecnológica (TRL5)**: Validar prototipo en un entorno relevante con demostraciones funcionales de AR y rutas en el mapa.
- **Control de Versiones y Repositorio**: Subir todo el código y la documentación a un repositorio GitHub público o privado, incluyendo:
  - Código fuente completo.
  - Historial de commits y ramas para cada módulo.
  - Issues y backlog de tareas.
  - Wiki o documentación adicional (diagramas UML, casos de uso, plan de pruebas).

## Roadmap / Próximos Pasos
- 📍 Integrar marcadores en MapScreen con rutas GPS.  
- 📱 Mejorar UI de HomeScreen (FlatList, detalles).  
- 🗄 Conectar con Firebase para datos en tiempo real.  
- 🎨 Incorporar modelos 3D y reconstrucciones históricas en AR.  
- 🧪 Pruebas de usuario y evaluación de impacto local.

## Licencia
MIT License  

---

> Desarrollado por [Tu Nombre] — Universidad / Semestre — Valledupar, 2025.

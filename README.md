# Social Media App

Una aplicación de redes sociales moderna construida con Next.js 14, TypeScript, Tailwind CSS y Firebase.

## 🚀 Características

- 🔐 Autenticación de usuarios con Firebase
- 📱 Diseño responsive con Tailwind CSS
- 🎨 UI moderna y atractiva
- ⚡ Rendimiento optimizado con Next.js 14
- 🔍 Búsqueda en tiempo real
- 📸 Soporte para imágenes y multimedia
- 💬 Sistema de comentarios y reacciones

## 🛠️ Tecnologías

- [Next.js 14](https://nextjs.org/) - Framework de React
- [TypeScript](https://www.typescriptlang.org/) - Superset tipado de JavaScript
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [Firebase](https://firebase.google.com/) - Backend y autenticación
- [Vitest](https://vitest.dev/) - Framework de testing
- [Testing Library](https://testing-library.com/) - Utilidades de testing

## 📦 Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/arklon1975/social-media-app.git
cd social-media-app
```

2. Instala las dependencias:
```bash
npm install
```

3. Configura las variables de entorno:
Crea un archivo `.env.local` en la raíz del proyecto con las siguientes variables:
```env
NEXT_PUBLIC_FIREBASE_API_KEY=tu_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=tu_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=tu_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=tu_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=tu_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=tu_app_id
```

4. Inicia el servidor de desarrollo:
```bash
npm run dev
```

## 🧪 Testing

El proyecto incluye una configuración completa de testing con Vitest y Testing Library. Para ejecutar las pruebas:

```bash
# Ejecutar todas las pruebas
npm test

# Ejecutar pruebas en modo watch
npm run test:watch

# Generar reporte de cobertura
npm run test:coverage

# Ejecutar pruebas con UI
npm run test:ui
```

## 📁 Estructura del Proyecto

```
src/
├── app/              # Rutas y páginas de Next.js
├── components/       # Componentes React reutilizables
├── lib/             # Utilidades y configuraciones
│   ├── firebase/    # Configuración de Firebase
│   ├── contexts/    # Contextos de React
│   └── hooks/       # Hooks personalizados
└── test/            # Configuración de pruebas
```

## 🚀 Scripts Disponibles

- `npm run dev` - Inicia el servidor de desarrollo
- `npm run build` - Construye la aplicación para producción
- `npm start` - Inicia la aplicación en modo producción
- `npm run lint` - Ejecuta el linter
- `npm test` - Ejecuta las pruebas
- `npm run test:watch` - Ejecuta las pruebas en modo watch
- `npm run test:coverage` - Genera reporte de cobertura
- `npm run test:ui` - Ejecuta las pruebas con UI

## 🤝 Contribuir

1. Haz un Fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE.md](LICENSE.md) para más detalles.

## 👥 Autores

- Tu Nombre - [@tu-usuario](https://github.com/tu-usuario)

## 🙏 Agradecimientos

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Firebase](https://firebase.google.com/)
- [Testing Library](https://testing-library.com/)

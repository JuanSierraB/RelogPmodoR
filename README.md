RelogPmodoR
Un temporizador Pomodoro implementado con arquitectura MVC (Modelo-Vista-Controlador) utilizando React y Vite. Esta aplicación te ayuda a gestionar tu tiempo de trabajo y descanso mediante la técnica Pomodoro.

Características
Temporizador de 25 minutos para trabajo y 5 minutos para descanso
Cambio automático entre modos de trabajo y descanso
Notificaciones sonoras al completar ciclos
Interfaz de usuario atractiva con animaciones
Tema verde relajante para la vista
Diseño responsive
Arquitectura MVC para una mejor organización del código
Arquitectura MVC
Este proyecto sigue el patrón Modelo-Vista-Controlador:

Modelo: Gestiona los datos y la lógica de negocio (TimerModel, SoundModel)
Vista: Componentes de UI (TimerDisplay, ControlButtons, ModeSelector)
Controlador: Conecta el modelo con la vista (TimerController)
Tecnologías Utilizadas
React 18
Vite
Tailwind CSS
shadcn/ui para componentes
Framer Motion para animaciones
Lucide React para iconos
Prettier para formateo de código
Requisitos Previos
Node.js (v14 o superior)
npm o yarn
Git
Instalación
Clona el repositorio:
git clone https://github.com/tu-usuario/pomodoro-timer.git
cd pomodoro-timer
Instala las dependencias:
npm install
# o
yarn
Inicia el servidor de desarrollo:
npm run dev
# o
yarn dev
Abre tu navegador en http://localhost:5173
Estructura del Proyecto
pomodoro-timer/
├── src/
│   ├── models/               # Modelos (lógica de negocio y estados)
│   ├── views/                # Componentes de vista (UI)
│   │   ├── components/       # Componentes reutilizables
│   │   └── pages/            # Páginas de la aplicación
│   ├── controllers/          # Controladores (conexión entre modelo y vista)
│   ├── utils/                # Utilidades y helpers
│   ├── hooks/                # Custom hooks
│   ├── constants/            # Constantes de la aplicación
│   ├── App.jsx              # Componente raíz
│   └── main.jsx             # Punto de entrada
├── public/                  # Recursos públicos
└── ...                      # Archivos de configuración
Deployment
Este proyecto está configurado para ser desplegado en Vercel:

Conecta tu repositorio de GitHub a Vercel
Configura los ajustes de build:
Build Command: npm run build
Output Directory: dist
Install Command: npm install
¡Despliega!
Gestión del Proyecto
Este proyecto utiliza GitHub Projects para la gestión de tareas. Puedes ver el tablero del proyecto aquí.

Scripts Disponibles
npm run dev: Inicia el servidor de desarrollo
npm run build: Construye la aplicación para producción
npm run preview: Vista previa de la versión de producción
npm run lint: Ejecuta el linter para encontrar problemas
npm run format: Formatea el código usando Prettier
Contribuir
Haz un fork del repositorio
Crea una rama para tu función (git checkout -b feature/amazing-feature)
Haz commit de tus cambios (git commit -m 'Add some amazing feature')
Haz push a la rama (git push origin feature/amazing-feature)
Abre un Pull Request
Licencia
Este proyecto está bajo la licencia MIT. Consulta el archivo LICENSE para más información.

Hecho con por Juan C. Sierra
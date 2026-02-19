# Chamba Lab 🚀

> **Community-Led Tech Platform**  
> *Democratizando el acceso a oportunidades laborales en tech para la comunidad local.*

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![CI Status](https://github.com/MeloDev2111/Chamba-Lab/actions/workflows/master-pipeline.yml/badge.svg)

## 📌 Misión
Nuestra misión es conectar talento local con oportunidades globales a través de colaboración (*Minka*) y recursos prácticos (*Cancha*). Sin floro, directo al grano.

## 🛠 Tech Stack
Este proyecto utiliza un stack moderno y eficiente:

- **Framework**: [Astro 5.x](https://astro.build) (Alto rendimiento por defecto)
- **UI Library**: React 18+ (Para interactividad selectiva)
- **Styling**: TailwindCSS 4.x (Utility-first)
- **Despliegue**: GitHub Pages (Static Site Generation)

## 🚀 Comenzando

### Prerrequisitos
- Node.js (v18 o superior)
- npm o pnpm

### Instalación

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/chamba-lab.git
   cd chamba-lab
   ```

2. Instala las dependencias:
   ```bash
   npm install
   ```

3. Inicia el servidor de desarrollo:
   ```bash
   npm run dev
   ```

## 📦 Despliegue y Versiones

El proyecto cuenta con un pipeline automatizado para gestionar versiones y despliegues (CI/CD).

### Scripts Disponibles

- `npm run dev`: Inicia servidor local.
- `npm run build`: Construye para producción.
- `npm run test`: Ejecuta las pruebas unitarias con Vitest.
- `npm run lint`: Ejecuta el linter y verificador de formato.
- `npm run release`: Ejecuta el proceso de release interactivo.
- `npm run changelog`: Genera el historial de cambios en `CHANGELOG.md`.

### Flujo CI/CD

Al hacer push a la rama `master`:
1.  **Validación**: Tests y linting.
2.  **Release**: `release-it` genera versión, tag y changelog.
3.  **Deploy**: Publicación automática en **GitHub Pages**.

> **Nota**: Es obligatorio usar [Conventional Commits](https://www.conventionalcommits.org/) (ej. `feat:`, `fix:`) para el versionado automático.

## 🤝 Contribución
¡Las contribuciones son bienvenidas! Por favor lee `AGENTS.md` para entender nuestros principios de diseño y flujo de trabajo.

1. Haz un Fork del proyecto
2. Crea tu rama de características (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'feat: Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia
Distribuido bajo la licencia MIT. Ver `LICENSE` para más información.

## 📞 Comunidad
- **Discord**: [Unirse a la conversación](https://discord.gg/TCuZSnfKTE)
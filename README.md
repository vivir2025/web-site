# Fundación Nacer Para Vivir - Sitio Web

Sitio web oficial de la **Fundación Nacer Para Vivir**, desarrollado con Astro. Página responsiva con información sobre programas, sedes, contactos y ecosistema digital.

## Características

- ✅ Página principal con hero interactivo
- ✅ Sección de programas y beneficios
- ✅ Información de 3 sedes (Cajibío, Piendamó, Morales)
- ✅ Formulario de contacto
- ✅ Chat widget integrado
- ✅ Responsive design (desktop, tablet, móvil)
- ✅ Navbar interactivo con menú hamburguesa
- ✅ Optimizado para SEO

## Tecnologías

- **Astro 6.1+** - Framework estático moderno
- **CSS3** - Responsive design
- **JavaScript Vanilla** - Interactividad
- **Leaflet.js** - Mapas interactivos
- **Sharp** - Optimización de imágenes
- **TypeScript** - Tipado estático

## Requisitos

- Node.js 22.12.0 o superior
- npm 10+

## Instalación

### 1. Clonar el repositorio

```bash
git clone https://github.com/fundacion-nacer/web-site.git
cd web-site
```

### 2. Instalar dependencias

```bash
npm install
```

### 3. Iniciar servidor de desarrollo

```bash
npm run dev
```

El sitio estará disponible en `http://localhost:4321`

## Comandos Disponibles

```bash
# Iniciar servidor de desarrollo
npm run dev

# Build para producción
npm run build

# Vista previa del build (requiere haber ejecutado build primero)
npm run preview

# Ejecutar comandos CLI de Astro
npm run astro -- [comando]

# Verificar código TypeScript y Astro
npm run astro -- check
```

## Estructura del Proyecto

```
visible-virgo/
├── public/                 # Archivos estáticos
├── src/
│   ├── assets/            # Imágenes y recursos
│   ├── components/        # Componentes reutilizables
│   │   ├── Benefits.astro
│   │   ├── CTA.astro
│   │   ├── FAQ.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── HowItWorks.astro
│   │   ├── Navbar.astro
│   │   └── Services.astro
│   ├── layouts/          # Layouts base
│   │   └── BaseLayout.astro
│   ├── pages/            # Páginas principales
│   │   └── index.astro
│   └── styles/           # Estilos globales
├── .gitignore            # Archivos a ignorar
├── astro.config.mjs      # Configuración de Astro
├── package.json          # Dependencias y scripts
└── tsconfig.json         # Configuración TypeScript
```

## Despliegue

### Vercel (Recomendado)

1. Conectar repositorio en [Vercel](https://vercel.com)
2. Astro se detecta automáticamente
3. Despliegue automático en cada push a `main`

### Netlify

1. Conectar repositorio en [Netlify](https://netlify.com)
2. Build command: `npm run build`
3. Publish directory: `dist`

### Hosting tradicional (cPanel, Cpanel, etc.)

1. Ejecutar: `npm run build`
2. Subir contenido de la carpeta `dist/` al servidor web
3. Configurar la raíz del sitio apuntando a `dist/`

## Variables de Entorno

No se requieren variables de entorno para el funcionamiento básico.

Para agregar en el futuro (si es necesario):
- Crear archivo `.env.local` en la raíz
- Declarar variables en `astro.config.mjs` si es necesario

## Contribución

1. Crear rama desde `main`: `git checkout -b feature/nombre-feature`
2. Realizar cambios
3. Commit con mensajes descriptivos: `git commit -m "feat: descripción"`
4. Push a la rama: `git push -u origin feature/nombre-feature`
5. Crear Pull Request

## Documentación Útil

- [Documentación oficial de Astro](https://docs.astro.build)
- [Guía de estructura de proyectos Astro](https://docs.astro.build/en/basics/project-structure/)
- [Referencia de APIs de Astro](https://docs.astro.build/en/reference/api-reference/)

## Soporte

Para reportar bugs o sugerencias, crear un issue en GitHub.

## Licencia

Todos los derechos reservados © 2026 **Fundación Nacer Para Vivir**

## Contacto

**Fundación Nacer Para Vivir**
- Email: fundacionnacerparavivir@gmail.com
- Web: [https://www.fundacionnacerparavivir.org](https://www.fundacionnacerparavivir.org)

---

**Última actualización:** 2 de junio de 2026

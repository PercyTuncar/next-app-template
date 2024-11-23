```markdown
# Plantilla de Next.js & NextUI - App Directory

Esta es una plantilla para crear aplicaciones utilizando Next.js 14 (App Directory) y NextUI.

LINK DEMO: https://next-app-template-vert.vercel.app/

## Cómo Usar

### Usar la plantilla con create-next-app

Para crear un nuevo proyecto basado en esta plantilla utilizando `create-next-app`, ejecuta el siguiente comando y asigna el nombre de tu proyecto:

```bash
npx create-next-app@latest nombre-del-proyecto -e https://github.com/PercyTuncar/next-app-template
```

### Esperar la instalación

El comando anterior instalará las dependencias y configurará tu proyecto automáticamente.

### Navegar al proyecto

Una vez finalizada la instalación, navega al directorio del proyecto:

```bash
cd nombre-del-proyecto
```

### Instalar dependencias (si no se instalaron automáticamente)

Si las dependencias no se instalaron automáticamente, puedes hacerlo manualmente usando uno de estos comandos. Ejemplo con `npm`:

```bash
npm install
```

### Ejecutar el servidor de desarrollo

Inicia el servidor de desarrollo con el siguiente comando:

```bash
npm run dev
```

### Configurar pnpm (opcional)

Si estás usando `pnpm`, necesitas agregar el siguiente código a tu archivo `.npmrc`:

```bash
public-hoist-pattern[]=*@nextui-org/*
```

Después de modificar el archivo `.npmrc`, ejecuta `pnpm install` nuevamente para asegurarte de que las dependencias se instalen correctamente.

## Tecnologías Utilizadas

- [Next.js](https://nextjs.org/docs/getting-started)
- [NextUI v2](https://nextui.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [next-themes](https://github.com/pacocoursey/next-themes)

## Licencia

Licenciado bajo la [licencia MIT](https://github.com/nextui-org/next-app-template/blob/main/LICENSE).
```
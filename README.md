# Plantilla de Next.js & NextUI - App Directory

Esta es una plantilla para crear aplicaciones utilizando Next.js (App Directory) y NextUI.

LINK DEMO: [https://next-app-template-vert.vercel.app/](https://next-app-template-vert.vercel.app/)

## ¿Cómo Usar?

### 1. Usar la plantilla con `create-next-app`

Para crear un nuevo proyecto basado en esta plantilla utilizando `create-next-app`, ejecuta el siguiente comando:

```bash
npx create-next-app@latest -e https://github.com/PercyTuncar/next-app-template
```

### 2. Agregar el nombre al proyecto

Cuando se te pida, asigna un nombre a tu proyecto. En este ejemplo, usaremos el nombre `my-project`.

### 3. Esperar la instalación

El comando anterior instalará las dependencias y configurará automáticamente tu proyecto llamado `my-project`.

### 4. Navegar al proyecto

Una vez finalizada la instalación, navega al directorio del proyecto. Como lo nombraste `my-project`, el comando sería:

```bash
cd my-project
```

### 5. Instalar dependencias (si no se instalaron automáticamente)

Si las dependencias no se instalaron automáticamente, puedes hacerlo manualmente usando uno de estos comandos dentro del directorio `my-project`. Ejemplo con `npm`:

```bash
npm install
```

### 6. Ejecutar el servidor de desarrollo

Inicia el servidor de desarrollo en tu proyecto `my-project` con el siguiente comando:

```bash
npm run dev
```

### Configurar `pnpm` (opcional)

Si decides usar `pnpm` en lugar de `npm`, necesitas agregar el siguiente código a tu archivo `.npmrc` dentro de `my-project`:

```bash
public-hoist-pattern[]=*@nextui-org/*
```

Después de modificar el archivo `.npmrc`, ejecuta `pnpm install` dentro de `my-project` para asegurarte de que las dependencias se instalen correctamente.

## Tecnologías Utilizadas

- [Next.js](https://nextjs.org/docs/getting-started)
- [NextUI v2](https://nextui.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Framer Motion](https://www.framer.com/motion/)
- [next-themes](https://github.com/pacocoursey/next-themes)

## Licencia

Licenciado bajo la [licencia MIT](https://github.com/nextui-org/next-app-template/blob/main/LICENSE).
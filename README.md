# web3d tutorial
Tutorial para la creación de una plantilla para la creación de sitios 3d con Nextjs, tailwind, 3rf and drei.

## PRIMEROS PASOS

### Instalación

- El primer paso es crear una app con nextjs.

```bash
npx create-next-app@latest
```

Dirígete [aquí](https://nextjs.org/docs/app/getting-started/installation) para más información

- Instala las dependencias necesarias:

```bash
npm install three @types/three @react-three/fiber @react-three/drei
```

Dirígete [aquí](https://r3f.docs.pmnd.rs/getting-started/introduction) para más información

## Preparación de la escena

- Entra al directorio recién creado con el nombnre de tu aplicación e introduce el siguiente código:

```bash
npm run dev
```

- Ajusta la nueva app de next y déjala sólo con lo escencial.

```tsx
// page.tsx

export default function Home() {
  return (
    <div>
      <h1>Hello</h1>
    </div>
  )
}
```

# AL-QUR'AN INSTITUTE

Aplicación web React + TypeScript + Vite para el estudio del árabe clásico fuṣḥā y el análisis lingüístico del Qur'an.

## Desarrollo

```bash
npm install
npm run dev
```

## Producción

```bash
npm run build
```

La salida estática se genera en `dist/`.

## Estado de esta versión

- Navegación funcional entre módulos.
- Currículo de 50 unidades organizado por niveles; primeras tres lecciones desarrolladas con ejercicios autocorregibles.
- Laboratorio demostrativo de قُلْ هُوَ اللَّهُ أَحَدٌ con fichas morfológicas y sintácticas.
- Diccionario y buscador de demostración.
- Módulos de tajwid y biblioteca preparados como estructura, no como sistemas completos.

## Integridad académica

Los análisis incluidos son material pedagógico demostrativo y requieren revisión experta. No se afirma que el corpus completo esté integrado. Cada futura fuente deberá registrar edición, licencia, versión, procedencia y política de normalización. No se deben inferir frecuencias ni análisis ausentes.

## Arquitectura futura

Separar corpus, análisis lingüísticos, traducciones, tafsir y audio de los componentes de interfaz. Añadir backend para sincronización, IA y procesamiento acústico; nunca exponer claves privadas en el cliente.

## Despliegue en Render

Static Site · Build command: `npm ci && npm run build` · Publish directory: `dist`.

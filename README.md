# Luis José Alarcón — primera versión web

Web de marca personal: finanzas personales, protección familiar, ahorro, planes universitarios y orientación sobre créditos. Diseño ejecutivo en azul marino y blanco.

## Incluye

- Mensaje «TU VIDA NO ES UN PRODUCTO FINANCIERO».
- Tres recorridos interactivos en «¿Qué quieres resolver hoy?».
- Servicios integrales, enfoque personal y preguntas frecuentes.
- Mensaje de consulta contextual que se puede copiar. No envía solicitudes ni recoge datos financieros.
- Casa y arco de protección en React Three Fiber / Three.js. Alternativa CSS dimensional cuando WebGL no está disponible.
- Botón de pausa y respeto de las preferencias de movimiento reducido.
- Diseño adaptable a móvil y teclado, diálogo de consulta y metadatos en español.

## Ejecutar

Usar Node 22 LTS o una versión compatible con Next.js 16.

    npm ci
    npm run dev

## Comprobar y exportar

    npm run build

La carpeta `out` contiene la exportación estática. Las dependencias están fijadas en package.json y package-lock.json.

## Estado

Rama para revisión, sin publicación ni dominio conectado. Indexación deshabilitada intencionalmente. Faltan WhatsApp y/o agenda confirmados y aprobación del diseño antes del lanzamiento.

La compilación fue comprobada. Se revisaron la portada, la selección de prioridad y el diálogo en navegador. El navegador remoto usa la alternativa sin WebGL; la escena WebGL debe probarse en un dispositivo compatible. Pendiente validar en el Samsung del titular.

## Origen y recursos

Adaptado de pmndrs/react-three-next, revisión bb29a61949601e1c563688faf33a12d062ec3710. Se conserva la licencia MIT original en LICENSE. El retrato se conserva únicamente en la vista previa local. No se incluye en el repositorio público hasta recibir autorización explícita. Sin ese recurso, la portada muestra una composición con las iniciales LJA. Para usar una fotografía autorizada en el futuro, añadir public/retrato.webp.

# Honda Dax de Luxe · El movimiento por dentro

Presentación web inmersiva estática, en español. Recorrido de nueve capítulos según `sustentacion 3.pptx`: proyecto, propuesta, objetivo, justificación, resultados, herramientas, recursos, conclusión y cierre.

Programa: **Técnica en Mantenimiento de Motos y Motocarros**. I. E. Carlos Julio Torrado Peñaranda, Ábrego. Integrantes: Mónica Rocío Torres Morales, Solmary Peñaranda Torrado, Karen Natalia Galván Palacio, Mariana Páez Pérez y Adriana Lucía Alsina Torrado.

## Referencia mecánica y alcance

- Manual Honda ST50/70 y CT70, páginas impresas 27–30, figuras 45–48 y selector: https://lilhonda.com/docs/CT70ShopManual.pdf . Arquitectura ST70 de tres marchas con dos horquillas. No se usa la variante CT70H de cuatro marchas.
- M1 integral al primario; M2 libre; M3 estriado y deslizante. C1 y C3 libres; C2 estriado y deslizante. 1.ª: C2 acopla C1. 2.ª: M3 acopla M2. 3.ª: C2 acopla C3. Punto muerto: sin camino completo de potencia hacia el secundario.
- Dentados 11/36, 18/31 y 21/25: catálogo Honda ST70N 1992, https://www.bike-parts-honda.ca/honda-motorcycle/70-MOTO/DAX/1992/ST70N/Engine/GEARBOX/13GANN41/E__1300/1/8665 . Se atribuyen a esta referencia; la presentación escolar no identifica año ni serie de su caja.
- Silueta exterior: fotos propias de la presentación y Honda ST70 clásica fotografiada en https://www.mathewsons.co.uk/auction/lot/lot-120---1987-honda-st-70-k3-dax/?lot=26198&sd=1 . Cárter orgánico, tapas circulares, cilindro horizontal, aletas y culata. Modelo procedural propio, no CAD del fabricante.
- Ambos pasadores siguen las mismas curvas que se dibujan como ranuras del tambor. Las piezas deslizantes conservan solapamiento axial con sus parejas. Velocidades de engranajes libres y solidarios se calculan por separado. Durante un cambio se interrumpe de manera idealizada el arrastre de salida hasta terminar la selección.
- Geometría, ranuras, separaciones, colores y tiempos didácticos; no se simulan cargas, rozamiento, inercia ni embrague centrífugo. No es un plano de fabricación.
- La conclusión de las diapositivas describe batería de 12 V, cables, portafusible y motor wiper. Su unión directa a la entrada de la caja se representa como integración didáctica: no se suministró un plano del acoplamiento.

## Contenido documentado

Siete fotografías de las diapositivas, herramientas y diez conceptos de presupuesto, suma verificada **$254.000 COP**. Se conserva el término «Hueso duro» de la fuente, sin asignarle un significado no confirmado. No se inventan resultados medidos del aprendizaje.

## Uso

Servir `dist/` mediante un servidor HTTP estático. Sin compilación ni dependencias remotas de ejecución. Scroll, enlaces de capítulos, flechas de teclado o controles inferiores. Giro libre, pausa, recentrado, selección N/1/2/3 y ciclo automático. El contenido puede leerse sin WebGL. Diseño adaptable a móvil y respeto de movimiento reducido.

Logos institucionales fijos, cada uno con su propio fondo blanco separado. Taller 3D continuo, fotos ampliables, banco de herramientas, mesa de presupuesto con billetes y cierre panorámico.

## Animación y licencias

Three.js r169 MIT; Fraunces, Manrope y DM Sans SIL OFL. Esquema SVG HyperFrames / GSAP, una línea de tiempo pausada y determinista, más adaptador web separado. Esquema sincronizado con la marcha elegida. El guion PDF está en `dist/assets/Guion_Caja_Honda_Dax.pdf`.

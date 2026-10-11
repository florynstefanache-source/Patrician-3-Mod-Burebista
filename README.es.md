[English](README.en.md) · [Página principal](README.md)

# Patrician 3 — Mod Burebista

**Edición estudiada: v24 · Barcos del mercado negro en Lübeck**  
**Autor del mod: Burebista**

Burebista amplía Patrician III con una taberna propia, encargos marítimos, tesoros, rescates de supervivientes, mercado negro, compra de barcos capturados, reputación y un proyecto de colonia. También incorpora una presentación visual personalizada: mapas, menús, fondos, barcos, iconos y paneles con ambientación marítima.

Esta edición reúne las mejoras anteriores y corrige la entrega de los barcos del mercado negro: aparecen en **Lübeck**, dañados y preparados para que el jugador ordene y pague su reparación en el astillero.

## Descarga

[Descargar Burebista v24 en GitHub](https://github.com/florynstefanache-source/Patrician-3-Mod-Burebista/releases/tag/v24)

El archivo completo se llama `Burebista_v24_BARCOS_MERCADO_NEGRO_LUEBECK.zip`.

## 1. Taberna de Burebista

Una taberna personalizada sirve como centro de las nuevas actividades.

- Acceso a encargos marítimos.
- Rumores sobre tesoros, tormentas y naufragios.
- Recogida de recompensas pendientes.
- Consulta de influencia y reputación.
- Donaciones para mejorar la reputación.
- Entrada al mercado negro pirata.
- Compra de barcos capturados.
- Acceso al proyecto de colonia Burebista.
- Fondo propio con pergamino, marco decorativo y retrato del personaje.

La guía incluida indica que se accede desde **Lübeck**, seleccionando el almacén hasta mostrar su panel **Warehouse** y la entrada de la taberna. La detección se basa en el panel del edificio, no en una posición fija del almacén.

## 2. Encargos y misiones marítimas

La taberna ofrece encargos de búsqueda, recuperación y rescate. Sus objetivos incluyen localizar naufragios, recuperar barriles y cargamentos o rescatar personas a la deriva.

El módulo incluye estos **15 nombres de encargos**:

| Encargo | Objetivo descrito |
| --- | --- |
| El navío perdido | Localizar los restos de un mercante y recuperar su carga. |
| Contrabando real | Encontrar barriles robados antes del regreso de los piratas. |
| El último superviviente | Encontrar una balsa y rescatar al marinero. |
| La herencia del capitán | Registrar un naufragio con documentos y botín. |
| Especias perdidas | Recuperar un cargamento valioso arrastrado por la corriente. |
| Mensajero en peligro | Rescatar a un emisario perdido en el Báltico. |
| Barco fantasma | Investigar unos restos avistados durante la noche. |
| Las pieles del norte | Encontrar fardos perdidos de una caravana marítima. |
| Capitán a la deriva | Salvar a un oficial. |
| Tesoro de la Hansa | Recuperar la caja del gremio de los restos de un navío. |
| Cargamento sin dueño | Recuperar barriles que flotan lejos de las rutas comerciales. |
| Náufrago misterioso | Rescatar a un hombre que afirma conocer una ruta secreta. |
| Restos de la tormenta | Buscar un barco hundido durante el último temporal. |
| Botín pirata | Localizar un cargamento abandonado tras una batalla naval. |
| Médico a la deriva | Rescatar a un cirujano. |

### Cómo completar un encargo

1. Entra en la taberna y elige **Encargos**.
2. Consulta el objetivo asignado.
3. Envía un barco al mar y navega hasta localizarlo.
4. Recoge o rescata el objetivo correspondiente.
5. Cuando aparezca el aviso de objetivo cumplido, vuelve a la taberna.
6. Pulsa **Recompensas** para cobrar.

Los mensajes del mod distinguen entre un encargo todavía activo, un objetivo completado y una recompensa pendiente. También avisan si no se ha podido entregar el premio, para volver a intentarlo.

## 3. Cofres, naufragios y supervivientes

- Cofres flotantes en el mapa naval, con gráfico propio.
- Registro de restos de naufragios y recuperación de su botín.
- Recuperación de mercancías y cargamentos valiosos.
- Rescate de marineros en balsas.
- Recompensa inmediata o una misión de transporte al siguiente puerto.
- Información marítima que puede revelar la posición de otro cofre.

### Rescate de marineros

La documentación de misiones indica este procedimiento:

1. Pasa con el barco sobre la balsa para rescatar al marinero.
2. Espera el mensaje que anuncia la recompensa o la misión.
3. Si pide transporte, entra en una ciudad.
4. Regresa al mapa de navegación para completar la entrega.

Entre las recompensas documentadas figuran **5.000–10.000 monedas**, mercancías valiosas, cargamentos recuperados e información sobre nuevos tesoros. La guía V1.1 describe una recompensa excepcional con **10 % de probabilidad**, que combina monedas y la posición de un nuevo tesoro. Son cifras de esa guía incluida; no se ha reconstruido el cálculo interno de v24.

## 4. Temporal y navegación

La base conserva el temporal naval y los eventos relacionados con tormentas, además del reloj y el mapa de expedición mencionados en sus notas de versión.

Los rumores de la taberna incluyen avisos sobre una tormenta fuerte en el Báltico y sobre naufragios con mercancías valiosas. El paquete también aporta gráficos de olas, icebergs, aves y marcadores para el mapa naval.

## 5. Reputación, influencia y descuento fiscal

- Pantalla de influencia y reputación de Burebista.
- Donaciones de **10.000**, **50.000** y **200.000 monedas**.
- Consulta de la reputación actual y del descuento fiscal activo.
- Guardado de reputación en `mods/burebista_reputacion.dat`, separado de los archivos normales de partida.
- Avisos si no hay dinero suficiente o si no se puede guardar la reputación.
- El mensaje de error indica que no se cobra una donación cuando falla su guardado.

El paquete no aporta una tabla legible de equivalencias entre donación, reputación y porcentaje fiscal; por eso no se atribuyen aquí porcentajes concretos.

## 6. Mercado negro pirata

El mercado negro permite comprar lotes de mercancía robada y consultar otras ofertas.

- Ofertas ambientadas en ataques a convoyes, saqueos de almacenes e interceptaciones en el Báltico.
- Presentación del precio total del lote.
- Entrega de mercancías a los barcos del jugador.
- Comprobación del espacio disponible en la bodega.
- Comprobación del dinero antes de completar la compra.
- Avisos cuando ningún barco puede cargar el lote.
- Mensaje de cancelación sin cobro si no se puede entregar la mercancía.
- Corrección de los precios de los productos del mercado negro, recogida en las notas de la base estable.

Los mensajes describen la mercancía como vendida por debajo del mercado. No se ha encontrado una tabla completa y legible de productos, cantidades y precios para publicarla como referencia fija.

## 7. Compra de barcos capturados

La taberna ofrece barcos capturados de los tipos **Sniqqa, Craier, Cog y Holk**, con los nombres usados por el propio módulo.

### Mejoras de v23 conservadas en v24

- Los barcos comprados se crean con el casco dañado.
- Se registran como propiedad del jugador.
- Antes de cobrar se validan el propietario, el tipo de barco, la ciudad, la posición y el enlace con la flota.
- La reparación no comienza automáticamente: el jugador debe ordenarla y pagarla en el astillero.
- El mantenimiento deja de forzar reparaciones automáticas de barcos normales.
- Las compras rechazadas muestran avisos de falta de dinero, espacio, flota válida o registro correcto.

### Corrección principal de v24

- Las compras nuevas se entregan en **Lübeck**.
- Los barcos **BOTIN** dañados que versiones anteriores enviaron por error a **Malmö** se recuperan automáticamente en Lübeck al cargar la partida.
- La recuperación no vuelve a cobrar la compra.
- Según la nota v24, esa corrección no modifica mercancías, colonia, fábricas ni construcciones.

Después de cargar, entra en Lübeck y espera unos segundos antes de revisar el puerto y el astillero.

## 8. Colonia y ciudad Burebista

El mod incorpora un proyecto de colonia con búsqueda de terreno, consulta de estado, contrato y comprobación de activación.

- Búsqueda de ofertas y emplazamientos mediante los datos nativos del juego.
- Diagnóstico de disponibilidad de terrenos.
- Solicitud y aceptación del contrato nativo.
- Mensajes para esperar el avance del tiempo y comprobar el estado.
- Activación de la ciudad y uso del nombre **Burebista** en el mapa y las ventanas urbanas.
- Acceso a la construcción nativa de la nueva ciudad.
- Diagnósticos cuando no hay terreno libre, otra misión del gobernador está activa o el contrato no se puede validar.

Las notas de la base completa documentan estas opciones de construcción:

| Grupo | Opciones documentadas |
| --- | --- |
| Producción | Todas las fábricas desbloqueadas en la base. |
| Urbanismo | Caminos —Road— y pozos —Well—. |
| Administración | Ayuntamiento —Town Hall—. |
| Servicios | Taberna —Tavern—. |
| Equipamiento militar | Fabricante de armas —Weaponsmith— y arsenal —Armoury—. |
| Puerto | Muelle de reparación —Repair Dock—. |
| Defensa | Bombarda del puerto —Port bombard— y bombarda de puerta —Gate bombard—. |
| Fortificación | Muralla —Town wall—, con registro válido de obra. |

**La base v22 excluye expresamente las pruebas posteriores de construcción instantánea de muralla.** v24 conserva esa base; no se anuncia aquí la muralla instantánea como función disponible.

Los mensajes internos hacen referencia a Windau y a identificadores urbanos concretos durante el desarrollo de la colonia. No significa que se añadan varios mapas nuevos independientes ni que cualquier partida tenga siempre un terreno disponible.

## 9. Cambios visuales e imágenes incluidas

El ZIP contiene **60 archivos de imagen**, contando el icono del lanzador, duplicados y variantes de prueba. Se han revisado visualmente. Esta cifra es el inventario del paquete, no una afirmación de 60 diseños originales distintos ni una comparación con una instalación limpia.

### Identidad visual y menús

- Menú principal personalizado con el nombre **Burebista**, ambientación marítima, pergamino, monedas y calavera decorativa.
- Icono del lanzador con retrato de personaje y marco dorado.
- Fondo de taberna propio en gran formato.
- Botones y marcos con decoración dorada.
- Fondos de puertos y barcos para carga, créditos, opciones, tutorial, guardar y cargar partida, fin de partida, configuración y pantallas multijugador.

Estos cambios de fondos multijugador son visuales: no implican nuevas funciones de red.

### Mapas y expediciones

- Mapa naval ilustrado, con marco decorativo y la firma Burebista.
- Paneles laterales con mapa, ilustraciones marítimas y motivos de brújula/calavera.
- Mapa del Mediterráneo para la pantalla de expediciones.
- Máscaras y configuraciones de mapa incluidas.
- Archivos de posiciones de ciudades, etiquetas y símbolos.

No se considera que cada mapa alternativo del ZIP se utilice simultáneamente: algunos son variantes conservadas en carpetas auxiliares.

### Barcos y flotas

- Hojas de imágenes para **Holk, Cog, Craier y Sniqqa**, con distintas orientaciones.
- Imágenes de barcos y convoyes navegando o fondeados.
- Panel de información naval, indicadores y cubierta de barco.
- Iconos de moral y contratación de tripulación con retratos de personajes.

Estas imágenes no prueban por sí mismas cambios en velocidad, capacidad de carga, armamento o comportamiento de los barcos.

### Edificios, eventos y objetos

- Interior de astillero con escena de trabajo portuario.
- Interior de herrería con artesano y herramientas.
- Interior de baños.
- Hoja gráfica de armas.
- Iconos del menú de construcción.
- Iconos de eventos marítimos y mercancías faltantes.
- Barril, indicador de bonus y cursor/pluma.
- Cofre flotante y una variante adicional de cofre.
- Hojas de olas, icebergs y aves del mapa naval.

### Archivos visuales de referencia

| Contenido | Archivos o carpetas del paquete |
| --- | --- |
| Menú principal | `images/Options/Hauptmenu.jpg` |
| Fondos de pantallas | `images/Background/` |
| Mapa naval | `images/Vollansichtskarte.bmp` |
| Paneles principales | `images/HauptscreenA1280.bmp`, `HauptscreenE.bmp`, `HauptscreenE1280.bmp` |
| Paneles laterales | `images/sidemenu/` |
| Comercio automático | `images/AutomatischerHandelBackground.bmp` |
| Botones de flota | `images/b_schiffe_anker.tga`, `b_schiffe_see.tga`, `b_konvoi_anker.tga`, `b_konvoi_see.tga` |
| Barcos | `images/Schiffe/page_mholk01.tga`, `page_mkogge01.tga`, `page_mkraier01.tga`, `page_mschnigge01.tga` |
| Construcción y cursor | `images/page_baumenue.tga`, `menu01.tga`, `feder0003.tga` |
| Eventos | `images/Ereignisse/` |
| Expediciones | `images/Expedition/Mittelmeer.bmp` |
| Interiores y armas | `images/Gebaeude_innen/` |
| Animaciones y cofre flotante | `images/Animationen_Seekarte/` |
| Taberna | `mods/taberna_burebista.bmp` |
| Cofre alternativo | `mods/cofre.bmp` |
| Icono del lanzador | `Burebista.ico` |

Los archivos con nombres como `-test`, `-buena` o `-modern` se conservan como variantes. Su presencia no garantiza que el juego los cargue. La configuración activa de texturas sí referencia, entre otros, el menú principal, los cuatro tipos de barcos, el mapa mediterráneo y varios paneles laterales.

## 10. Resolución, interfaz y correcciones

- Configuración de mapa para **1920 × 1080** en `scripts/accelMap.ini`.
- Scripts de pantalla y texturas incluidos en el paquete.
- Configuraciones de ciudades en `StadtDaten.ini` y `cities_modified.txt`.
- Corrección del chat y del foco integrada en el módulo principal, según la documentación de la base estable.
- Comprobaciones del ejecutable antes de activar determinados cambios de construcción y defensa.

El ZIP **no incluye** `Patrician3_1920x1080.exe`. El lanzador Burebista contiene una comprobación que lo exige. Aunque el archivo BAT dispone de alternativas, si encuentra `Burebista.exe` lo abre primero; por eso no se garantiza esta edición sobre cualquier ejecutable original o resolución.

## 11. Instalación

1. Cierra Patrician III y el lanzador Burebista.
2. Extrae **todo el ZIP** en una carpeta normal.
3. Ejecuta `INSTALAR_BUREBISTA.bat` y acepta la solicitud de administrador.
4. El instalador busca el juego en las rutas habituales de Steam; si no lo encuentra, permite elegir la carpeta.
5. Espera el mensaje de instalación completada.
6. Abre el acceso directo **Burebista** creado en el escritorio, o `INICIAR_BUREBISTA.bat`.

No ejecutes el instalador desde dentro del ZIP.

### Qué hace el instalador

- Comprueba que el juego y el lanzador estén cerrados.
- Copia imágenes, scripts, módulos y lanzador.
- Crea una carpeta `BACKUP_BUREBISTA_fecha_hora` con los archivos existentes que vaya a sustituir.
- Evita copiar un archivo sobre sí mismo si el paquete se extrajo dentro del juego.
- Añade la sección de textura del cofre flotante si falta.
- Verifica la presencia de los componentes principales.
- Comprueba por SHA-256 que el motor instalado corresponde a v24.
- Crea un acceso directo con el icono de Burebista.

Si extraes directamente sobre la instalación y sobrescribes archivos antes de ejecutar el instalador, este no puede recuperar por sí solo las versiones originales ya reemplazadas. Para conservarlas, extrae primero en una carpeta separada.

## 12. Archivos necesarios y datos del mod

Los dos módulos siguientes son necesarios y no deben separarse:

- `mods/cofres_navales.dll`: carga las correcciones actuales y el módulo estable.
- `mods/cofres_navales_estable.dll`: contiene el núcleo de taberna, mercado, barcos, misiones y colonia de esta edición.

Aunque el segundo archivo conserve el nombre «estable», el instalador verifica que su contenido sea el correspondiente a **v24**.

Otros archivos relevantes:

- `Burebista.exe`: lanzador.
- `Burebista.ico`: icono.
- `mods/taberna_burebista.bmp`: interfaz de taberna.
- `images/Animationen_Seekarte/cofre_flotante.tga`: gráfico del tesoro.
- `scripts/`: ajustes de pantalla, ciudades y texturas.

El módulo contiene rutas de datos y diagnósticos de reputación, colonia, mercado, barcos y construcción dentro de `mods`. No todos esos informes tienen por qué existir antes de usar la función correspondiente. La reputación se guarda fuera del archivo normal de partida; conviene conservar también los datos del mod al trasladar una instalación.

## 13. Evolución resumida

| Etapa documentada | Aportación |
| --- | --- |
| V1.1 — Misiones | Rescate de marineros, entrega en puerto y recompensas aleatorias. |
| Taberna beta | Centro de encargos, rumores y recompensas desde el almacén de Lübeck. |
| Base estable ampliada | Taberna, reputación, descuento fiscal, mercado negro, mercancías, barcos, colonia y corrección de chat/foco. |
| v20 | Base completa con fábricas, servicios, defensas y muralla con registro válido de obra. |
| v22 | Consolidación estable y mejoras del registro/entrega de barcos; excluye pruebas posteriores de muralla instantánea. |
| v23 | Barcos dañados y reparación ordenada y pagada por el jugador. |
| v24 | Entrega en Lübeck y recuperación de barcos BOTIN enviados por error a Malmö. |

## 14. Alcance de esta revisión

Este README se ha elaborado estudiando el ZIP v24: sus ocho documentos TXT, instaladores, scripts, 60 imágenes y textos legibles de los módulos. No se han ejecutado los binarios ni se ha realizado una partida de prueba durante la revisión.

Las funciones se describen según la documentación y los mensajes incluidos. Los textos internos permiten identificar menús, encargos y controles de error, pero no sustituyen una comprobación completa del código y su funcionamiento. No se atribuyen cifras o mecánicas que no se hayan podido respaldar.

Algunos LEEME son históricos y se contradicen: uno describe una edición anterior a la colonia, mientras otros documentan su activación. Para esta edición se ha dado prioridad a las notas **v24, v23 y v22**, conservando las funciones anteriores que estas indican mantener.

No se incluyen como mejoras confirmadas estadísticas navales nuevas, cambios de inteligencia artificial, nuevos productos, multijugador ampliado ni construcción instantánea de murallas.

Mod no oficial para **Patrician III**. Requiere una instalación compatible del juego.

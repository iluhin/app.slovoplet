[Русский](README.md) · [English](README.en.md) · **Español** · [简体中文](README.zh-CN.md)

<div align="center">

<img src="cover.png" alt="Словоплёт, juego de palabras">

# Словоплёт

**Adivina la palabra de cinco letras.** Diccionario ruso, clasificación, ocho temas —
y un juego que sigue funcionando en el metro.

[**▶ Jugar en el navegador**](https://5bukv.iluh.in/) ·
[**⬇ Descargar para Android**](https://5bukv.iluh.in/update.php?a=download) ·
[**📖 Wiki**](../../wiki)

</div>

---

## Reglas

Introduce una palabra de cinco letras y el juego coloreará cada letra:

| | |
|---|---|
| 🟨 | la letra está en el lugar correcto |
| 🟦 | la letra aparece en la palabra, pero en otro lugar |
| ⬜ | la letra no aparece en la palabra |

Tienes cinco intentos. Hay dos modos: «Случайное слово» (Palabra aleatoria)
y «Слово дня» (Palabra del día), la misma para todos hasta medianoche.
Las partidas cuentan para la clasificación general si has creado un perfil;
también puedes jugar como invitado.

## Temas

Ocho temas: seis esquemas de color tranquilos y dos con carácter.

- **Cuaderno** — una hoja cuadriculada con margen, hojas rayadas en las
  ventanas, letras escritas a mano y casillas que no se rellenan, sino que
  se colorean: con rotulador fluorescente, bolígrafo azul o lápiz.
- **Tiempo** — el tablero vive el tiempo que hace ahora en tu ventana: un
  rayo de sol que broncea las letras, estrellas de noche, hojas al viento,
  gotas en el cristal y filas que se mojan, gorros de nieve y hielo cuando
  hiela. Para quien tiene perfil. La ciudad la determina nuestro propio
  servidor con su propia base de datos, sin pedir la ubicación y sin
  enviar tu dirección a nadie ([detalles](https://5bukv.iluh.in/privacy.html)).

Ambos ya están en el sitio web y llegarán a la aplicación con la versión 2.8.

## Aplicación para Android

- **Funciona sin conexión.** El tablero, el teclado y el diccionario están
  incluidos en la aplicación: la partida empieza al instante, incluso sin
  conexión. La palabra del día y la clasificación siguen dependiendo del
  servidor — [por qué](../../wiki/Offline).
- **Tiene personalidad.** De vez en cuando, el juego comenta lo que ocurre:
  detecta si abusas de una misma letra, fallas tres palabras o ganas al primer
  intento. Como máximo una vez por partida, y nunca a costa del jugador.
- **Mide el tiempo con justicia.** El cronómetro solo avanza mientras el juego
  está abierto en pantalla: al minimizarlo, se detiene. Una partida alargada
  por pausas prolongadas no cuenta para tu récord personal de tiempo, por lo
  que los récords son comparables.
- **Avisa de las actualizaciones.** El juego anuncia las nuevas versiones
  con su número, tamaño y lista de cambios. El navegador descarga el archivo
  y ofrece instalarlo. Si instalaste el juego desde una tienda, esa tienda
  se encarga de actualizarlo.
- **Se abre en una pantalla de inicio que invita a jugar.** Una sola pantalla:
  una pregunta, un botón y tres enlaces de navegación. Las partidas sin terminar
  se abren directamente, sin pasos adicionales.
- **Nada de más.** Unos 600 KB, sin publicidad ni rastreadores. El juego no
  solicita ningún permiso que tengas que conceder: ni cámara, ni contactos,
  ni ubicación, ni instalación de paquetes.
- **Requiere** Android 7.0 o posterior.

Descarga el archivo de la [página de versiones](../../releases) o directamente
[del sitio web](https://5bukv.iluh.in/update.php?a=download): está firmado con
la misma clave, por lo que la actualización se instala sobre el juego existente.

## Ordenador e iPhone

El sitio web es una PWA, así que se instala como una aplicación normal: su
propia ventana sin barra de direcciones, un icono en el menú Inicio o en la
pantalla de inicio, y arranca sin conexión.

- **Windows.** Se está preparando la publicación en Microsoft Store; los
  paquetes ya compilados están en [`msstore/`](msstore/). Mientras tanto,
  abre [el juego](https://5bukv.iluh.in) en Edge y pulsa el icono de
  instalación de la barra de direcciones: es exactamente la misma aplicación.
- **iPhone y iPad.** No hay una aplicación independiente: «Поделиться»
  (Compartir) → «На экран „Домой“» (Añadir a la pantalla de inicio).
- **Chrome** en cualquier sistema: menú «⋮» → «Установить приложение»
  (Instalar aplicación).

La versión para Windows tiene algo que el APK no tiene: el paquete no
contiene una copia del juego, sino la dirección del sitio web, así que las
nuevas versiones llegan solas, sin actualizar la aplicación.

## AppGallery

En AppGallery el juego sale con otro nombre de paquete:
`com.iluhin.slovoplet` en lugar de `com.iluhin.fiveletters`, porque la tienda
no cedió el original. Eso significa que la versión de AppGallery no se
actualizará a la del sitio web ni al revés, y que ambas pueden convivir en el
mismo teléfono. El perfil y las estadísticas son los mismos en cualquier
caso: están en el servidor.

## Historial de versiones

Todas las versiones y sus descripciones están en la [página de versiones](../../releases):
desde la primera aplicación contenedora, la 1.4, hasta la actual. El archivo más
reciente siempre está en la [última versión](../../releases/latest), y el sitio
web ofrece ese mismo archivo.

## Qué contiene este repositorio

Solo versiones e información sobre el juego: notas de las versiones, paquetes
de compilaciones anteriores, los paquetes para Microsoft Store y la wiki. El código fuente del sitio web y de
la aplicación sigue siendo cerrado por ahora.

Esta rama es el **canal estable**: toda la historia del juego desde la 1.4
hasta la versión actual. También existe la rama [beta](../../tree/beta), un
canal independiente donde se prueban las actualizaciones parciales de la
aplicación sin reinstalarla. Sus compilaciones se marcan como versiones
preliminares y no aparecen en «Latest».

## Preguntas y sugerencias

[Issues](../../issues): si el juego rechaza una palabra válida, algo falla
o tienes una idea.

---

© Илья Анисимов · [iluh.in](https://iluh.in)

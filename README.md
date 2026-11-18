# Serena S.O.S. — demo

Prototipo de la app Serena S.O.S. (proyecto universitario, CIDE).

- App para celular: abre `index.html` desde la dirección de GitHub Pages de este repositorio.
- Versión para computador (teléfono + panel de demostración): `prototipo.html`.
- Simulacro en vivo (solo la simulación, muy sensible, para demostraciones moviendo una mesa): `simulacro.html`.
- Portal de Rescate para rescatistas, personal médico y Policía (computador y celular): `rescate.html`. Si pides ayuda en la app desde el mismo navegador, el pedido aparece en el portal.
- Serena Campus, portal para universidades, colegios y empresas (ejemplo: CIDE): `campus.html`. La institución crea códigos de vinculación con su QR, lanza simulacros y ve en vivo quién está bien, quién pide ayuda y quién no ha respondido. En la app, cada persona se vincula en Perfil → Mi institución, con el código o escaneando el QR. Los pedidos de ayuda de las personas vinculadas llegan a la brigada y al portal de Rescate.

El simulacro por sacudida usa el acelerómetro del celular, que solo funciona desde una dirección https en Chrome (Android) o Safari (iPhone).

Para que Serena Campus funcione entre dispositivos, Firestore necesita las reglas nuevas (colecciones `codigos` e `instituciones`). Sin ellas, el portal y la app funcionan en el mismo navegador.

## Créditos

- Voz: Fernando, generada con [ElevenLabs](https://elevenlabs.io). Uso académico, no comercial.
- Códigos QR: [qrcode-generator](https://github.com/kazuhikoarase/qrcode-generator) de Kazuhiko Arase, licencia MIT.

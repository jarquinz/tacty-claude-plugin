![Tacty](assets/icon.png)

# Tacty for Claude

Tacty gives any local business a digital loyalty card. Customers tap an NFC tag or scan a QR code, become members without downloading anything, and save the card to Apple Wallet or Google Wallet. With this plugin, Claude becomes the owner's sales partner: it creates the card by chatting, reads who is coming and who the business is losing, and, only after the owner confirms, sends notices to customers' cards, publishes promotions and turns on automations.

*Español abajo.*

## What's inside

- **Tacty connector (remote MCP server):** `https://www.tacty.co/mcp`, over HTTPS with OAuth 2.1 (PKCE). You sign in with your Tacty account; the plugin stores no credentials.
- **Skill `tacty-sales-partner`:** teaches Claude the Tacty workflows: setting up a card, the weekly check-in, winning back customers at risk, filling slow hours, and demo mode.

## What it runs, sends and fetches

The plugin runs no local code, hooks or scripts. Everything goes through the Tacty connector above, which only talks to `www.tacty.co`. Data you read (customers, visits, analytics) stays in your Tacty account. Messages to customers are delivered by Tacty to their Apple Wallet or Google Wallet passes, and Claude always asks you to confirm the exact text and audience before sending.

## Requirements

- A Tacty account (business owner or reseller). Sign up at https://www.tacty.co.
- Resellers can say "Let's go into demo mode" to work with a demo café that has realistic sample data.

## Try it

- "Create a loyalty card for my barbershop: 8 haircuts and the 9th is free. Give me the QR to print."
- "Which customers am I losing? Send them a nudge to come back."
- "What are my slowest hours? Create a promotion for them."
- "Who are my 10 best customers and how often do they come?"
- "Turn on the birthday message with a free dessert."

## Links

- Docs: https://www.tacty.co/docs/asistentes
- Privacy: https://www.tacty.co/privacidad
- Terms: https://www.tacty.co/terminos
- Support: hola@tacty.co

---

## Tacty para Claude (español)

Tacty le da a cualquier negocio una tarjeta de fidelización digital: el cliente toca o escanea (NFC y QR), se hace miembro sin bajar nada y guarda la tarjeta en Apple Wallet o Google Wallet. Con este plugin, Claude es el compañero de ventas del dueño: crea la tarjeta conversando, le dice quién viene y quién se está perdiendo, y con su confirmación manda avisos a la tarjeta de sus clientes, crea promociones y enciende automatizaciones. Inicias sesión con tu cuenta de Tacty; el plugin no guarda contraseñas ni ejecuta código en tu equipo.

## License

MIT. Copyright Central Digital Network LLC.

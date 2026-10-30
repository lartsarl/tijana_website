# Tijana — personal trainer website

Responsive Serbian static website inspired by the layout and charcoal/yellow palette of anajakovljevic.com. Original implementation, copy, and T monogram. No package installation or build required.

## Preview

Serve `dist/` with any static server, for example `python -m http.server 8080 --directory dist`.

## Before launch

- Confirm the trainer name, biography, services, program details and prices. Current copy and program names are working proposals, not verified business facts.
- Replace illustrative Unsplash photos with the trainer's approved photographs. Sources: https://unsplash.com/photos/1518611012118-696072aa579a (image endpoint ID), https://images.unsplash.com/photo-1517836357463-d25dfeac3438.
- Add official contact and social links. The consultation form currently downloads a local text request; it sends and stores nothing remotely. Connect a real contact service before changing the button to a sending action.
- Add consented testimonials only when supplied. No client claims or statistics are invented.
- Review privacy/legal requirements for any future data collection or payments.

## Files

- `dist/index.html`: page sections and editable content
- `dist/style.css`: responsive design
- `dist/app.js`: navigation, program dialogs, request download
- `dist/assets/`: illustrative photography

Google Fonts loads DM Sans and Montserrat with system fallbacks. Hosting uses `dist/` as its static root.

python -m http.server 8080 --bind 127.0.0.1 --directory dist

# 🤖 PistorAI – Der offizielle Pistor-Chatbot

**PistorAI** ist der offizielle unternehmensweite Chatbot der Pistor AG.  
Er wurde entwickelt, um Mitarbeitende bei geschäftsrelevanten Fragen zu unterstützen – effizient, intern abgestimmt und rund um die Uhr verfügbar.

## 🚀 Funktionen

- Beantwortung interner Fragen rund um Pistor
- Integration mit Azure OpenAI
- Anpassbares Branding (Logo, Titel, Beschreibung)
- Webchat-Frontend auf Basis von Vite

## ⚙️ Konfiguration (Umgebungsvariablen)

| Variable                | Beschreibung                          |
|-------------------------|----------------------------------------|
| `UI_CHAT_LOGO`          | Logo (z. B. `/static/pistor-logo.png`) |
| `UI_CHAT_TITLE`         | Titel oben im Chat (z. B. `Pistor`)    |
| `UI_CHAT_DESCRIPTION`   | Beschreibung unter dem Titel           |

> Bilder gehören ins Verzeichnis `frontend/public/static/`.

## 🔧 Lokales Setup

```bash
git clone https://github.com/daveram123/PistorAI.git
cd PistorAI/frontend
npm install
npm run dev

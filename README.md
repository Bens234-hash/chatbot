# HU-Chatbot

Een React-gebaseerde chatbot die gebruik maakt van OpenAI's Assistant API.

## Setup

1. **Clone het project en installeer dependencies:**
   ```bash
   npm install
   ```

2. **Configureer environment variables:**
   
   Kopieer `.env` en vul je OpenAI credentials in:
   ```bash
   cp .env .env.local
   ```
   
   Bewerk `.env.local` en vul in:
   ```
   VITE_OPENAI_API_KEY=sk-your-actual-openai-api-key
   VITE_OPENAI_ASSISTANT_ID=asst_your-actual-assistant-id
   ```

3. **OpenAI API Key verkrijgen:**
   - Ga naar [OpenAI Platform](https://platform.openai.com/api-keys)
   - Log in of maak een account aan
   - Klik op "Create new secret key"
   - Kopieer de key en plak deze in je `.env.local` bestand

4. **Assistant ID verkrijgen:**
   - Ga naar [OpenAI Assistants](https://platform.openai.com/assistants)
   - Maak een nieuwe Assistant aan of gebruik een bestaande
   - Kopieer de Assistant ID (begint met `asst_`)
   - Plak deze in je `.env.local` bestand

5. **Start de development server:**
   ```bash
   npm run dev
   ```

## Features

- Real-time chat met OpenAI Assistant
- Responsive design
- Error handling
- Loading states
- Nederlandse interface

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- OpenAI Assistant API

## Beveiliging

⚠️ **Belangrijk**: Voeg nooit je echte API keys toe aan version control. Het `.env` bestand bevat alleen placeholder waarden.
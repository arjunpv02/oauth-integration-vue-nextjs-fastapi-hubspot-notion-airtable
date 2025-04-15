# oauth-integration-vue-nextjs-fastapi-hubspot-notion-airtable
OAuth Integration with HubSpot, Notion, and Airtable using Vue.js &amp; FastAPI.

📌 Project Title
VectorShift OAuth Integration: HubSpot, Notion & Airtable using Vue.js (Vite), Next.js & FastAPI


🔧 Tech Stack
Frontend: Vue.js, Next.js (with Vite)

Backend: FastAPI (Python)

OAuth: HubSpot authorization with credential handling

Others: Redis (via Upstash), REST APIs

✔️ Key Implementations
Completed the full OAuth flow for HubSpot:

authorize_hubspot

oauth2callback_hubspot

get_hubspot_credentials

get_items_hubspot

Integrated HubSpot UI elements with the frontend

Tested using personal HubSpot OAuth client credentials

Displayed fetched items via console (demo mode)


⚙️ Frontend
✅ Switched to Vite (instead of CRA)
Replaced create-react-app with Vite

Updated package.json, vite.config.js, and project structure

Installed required dev dependencies

💡 Why Vite?
Faced version & dependency issues with react-scripts, npm, and node

Vite provided a quicker, smoother setup

No functionality was affected — works 100% the same! ✌️💯👌

🖥️ Backend
✅ Redis Setup via Upstash
Used Upstash Redis (cloud-hosted)

Updated Redis config to use Upstash URL and credentials

💡 Why Upstash?
Avoided setting up local Redis server

Faster testing and simpler config

🚀 Run Instructions

Frontend
npm i
npm run dev


Backend
uvicorn main:app --reload


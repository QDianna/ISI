# Vacation Planner App (Next.js)

Proiect realizat pentru cursul **Integrarea Sistemelor Informatice**, în cadrul căruia am dezvoltat o aplicație web pentru planificarea vacanțelor pe baza unor obiective turistice tematice.

## Descriere
Aplicația permite utilizatorilor:
- să exploreze hărți interactive  
- să aleagă obiective turistice în funcție de o tematică preferată (relaxare, istoric, cultural etc.)  
- să își planifice un itinerariu personalizat pentru vacanță  

Sistemul oferă rute și sugestii pe baza destinațiilor selectate.

## Rol în echipă
- Am contribuit la **front-end** (interfață utilizator, integrarea cu hărțile, afișarea obiectivelor turistice)  
- Am lucrat parțial și la **back-end**, în special la rutarea destinațiilor și logica de planificare  

## Tehnologii
- **Next.js** pentru front-end și server-side rendering  
- **React** pentru componente interactive  
- Integrare API pentru hărți și obiective turistice (ex. Google Maps / Leaflet / alt API)  
- **Node.js** pentru logica de back-end și rutare  

## Funcționalități
- Vizualizarea hărții și a obiectivelor turistice marcate  
- Selectarea tematicii vacanței (relaxare, istoric, cultural)  
- Generarea unui traseu personalizat  
- Planificarea vacanței prin salvarea destinațiilor

## Setup
First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

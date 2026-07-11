# Keith Daily Brief App - 113°F La Quinta
### HEY KEITH, EVENING! - Live Weather + Top Stories + Play Briefing

## 🔄 Cloud Sync Flowchart - GitHub, Netlify, Vercel & Supabase

> Desktop Chrome + iPhone Safari stay synced via Supabase Cloud - No LocalStorage

```mermaid
flowchart TD
    A[Chrome - Write Code] --> B[GitHub shiny-funicular]
    B --> C[Netlify keith-brief-app.netlify.app]
    B --> D[Vercel keith-brief-app.vercel.app]
    C --> E[Env Vars SUPABASE_URL + KEY + OPENAI]
    D --> E
    E --> F[Supabase Cloud DB - No LocalStorage]
    E --> G[OpenAI]
    F --> H[Live UI HEY KEITH EVENING! 113°F + Top Stories]
    G --> H
    H --> I[Desktop + iPhone Synced]
    I --> J[URL Share -> Notes]
    J --> F# shiny-funicular
Morning briefing 

# inventory-service

> Repository di prova per Code Guardian. Simula un piccolo servizio di gestione inventario (ricerca prodotti, autenticazione, report), con alcune vulnerabilità introdotte deliberatamente per testare l'agente OWASP, e alcune funzioni prive di documentazione per testare l'agente Docs.

> Non è codice reale: non eseguirlo, serve solo come fixture di analisi.

## Table of Contents
- [Features](#features)
- [Project Structure](#project-structure)
- [License](#license)

## Features
- Finta API di gestione inventario
- Funzionalità di autenticazione simulata
- Generazione di report fittizi
- Progettato solo per testare sistemi di analisi (OWASP, agenti Docs)
- Include componenti senza documentazione
- Include vulnerabilità deliberatamente aggiunte per test

## Project Structure
Il progetto è costituito da pochi file Python all'interno della directory `src/`.

```text
src/
├── auth.py     # Gestione autenticazione simulata
├── db.py       # Mockup database fittizio
├── reports.py  # Funzionalità di report
└── utils.py    # Strumenti comuni
```

## License
Non è specificata alcuna licenza.

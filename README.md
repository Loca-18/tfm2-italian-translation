# Traduzione Italiana — Teamfight Manager 2

Traduzione fan-made completa in italiano per [Teamfight Manager 2](https://store.steampowered.com/app/3009300).  
Pubblicata su Steam Workshop: [Traduzione Italiana](https://steamcommunity.com/sharedfiles/filedetails/?id=3739767283)  
Autore: **Loca**

## Copertura

| File | Contenuto | Stringhe |
|------|-----------|----------|
| `ui.i18n` | Interfaccia completa | ~700 |
| `athlete.i18n` | Statistiche giocatori | 52 |
| `news.i18n` | Notizie ed eventi | 906 |
| `champion.i18n` | Descrizioni champion | ~288 |
| `item.i18n` | Oggetti | 105 |
| `object.i18n` | Oggetti di gioco | 108 |

## Workaround tecnico

Il dropdown delle lingue è hardcoded nell'eseguibile e non può essere esteso via mod.  
Questa traduzione riutilizza lo slot turco (`tr`) come vettore per l'italiano:
- Lo slot `tr` viene rietichettato "Italiano" nella UI
- Viene pre-popolato con contenuto inglese completo (il motore non fa fallback cross-locale)
- Le traduzioni italiane vengono sovrapposte

**Conseguenza:** il turco non è disponibile finché questa mod è attiva.  
Per una soluzione pulita sarebbe necessario il supporto nativo del locale `it` da parte degli sviluppatori.

## Convenzioni

- Nomi dei champion → mantenuti in inglese
- Termini gaming → mantenuti in inglese (ban/pick, jungle, draft, KDA, MVP…)
- Tono → naturale e scorrevole, adatto a un videogioco

## Installazione (via Workshop)

1. Iscriviti alla mod su Steam Workshop
2. Avvia il gioco → **Mods** → attiva **Traduzione Italiana**
3. Riavvia → **Opzioni → Lingua → Italiano**
4. Se usi altri mod, posiziona questa mod **in fondo alla lista**

## Licenza

Fan translation — solo per uso non commerciale.  
Tutti i testi originali sono proprietà di Team Samoyed.

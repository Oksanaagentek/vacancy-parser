# Vacancy Parser

Mobile-first prototype for composing a one-source vacancy query.

## Current scope

- One source per request: HH.ru, Monster.com, or a LinkedIn trial mode.
- Publication period: 7, 30 (default), or 90 days.
- Optional composable filters: role title, any number of required skills, location, work format, visa support, salary, and employer.
- All enabled filters are combined with AND logic.
- The page is a prototype only: it does not yet collect vacancies or send email.

## Run locally

```bash
python3 -m http.server 4173
```

Then open `http://127.0.0.1:4173/`.

## Privacy and safety

No personal data, email addresses, access tokens, or saved search results belong in this public repository. Credentials must remain in private secret storage.

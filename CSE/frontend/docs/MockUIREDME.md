# UTA Swag Dispenser ‑ Mockup Frontend

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Overview
This is the frontend mockup for the **UTA Swag Dispenser** built using Angular 20 and standalone components, with PrimeIcons used for iconography.  
It is designed for a swag‑vending machine style UI (play mini‑games, view swag inventory, admin panel).

## Prerequisites
- Node.js v22.16.0 (or newer)
- npm (latest LTS recommended)
- Git
- GitHub repo access: `https://github.com/Aweksha/SwagOverflow`

## Getting Started

```bash
# 1. Clone the repo
git clone https://github.com/Aweksha/SwagOverflow.git
cd SwagOverflow/CSE/frontend/swag-kiosk

# 2. Install dependencies
npm install

# 3. Start the dev server
npm start

# App runs at: http://localhost:/
```

## Project Structure

```
swag-kiosk/
  src/
    app/
      pages/
        home/
        admin/
        games/
    styles.scss
    index.html
```

## Key Technologies

| Library     | Version   | Notes                        |
|-------------|-----------|------------------------------|
| Angular     | ^20.3.7   | Latest stable major version  |
| PrimeIcons  | ^7.0.0    | Icons only (no PrimeNG CSS) |

## Styles & Icons

PrimeIcons must be imported in `src/styles.scss`:

```scss
@import 'primeicons/primeicons.css';
```

Use icons in components like this:

```html
<i class="pi pi-gift"></i>
```

## GitHub Token Setup (for private repo access)

1. Go to GitHub → **Settings > Developer Settings > Tokens (Classic)**  
2. Generate a token with `repo` scope
3. Clone using:
```bash
git clone https://<TOKEN>@github.com/Aweksha/SwagOverflow.git
```

> Replace `<TOKEN>` with your actual GitHub token.

MIT License © 2025 UTA CSE Team

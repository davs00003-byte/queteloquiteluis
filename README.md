# Queteloquiteluis

Website for Queteloquiteluis — laser tattoo and permanent-makeup removal by Luis Deu Peña, Gran de Gràcia 254, Barcelona.

- Live: https://queteloquiteluis.vercel.app
- Languages: Català · Castellano · English
- Stack: single static page (`public/index.html`) + images in `public/img/`. No framework.

## Edit common settings
Open `public/index.html` and search for `CONFIG`:
- `EMAIL` — Luis's email (shown in contact list and footer when set)
- `PRICE_DRAFT` — set to `false` once real prices are confirmed
- `SIZES`, `MICRO_PRICE`, `SESSIONS` — price calculator values
- Copy for all three languages lives in the `T` object.

Every push to `main` deploys to Vercel automatically.

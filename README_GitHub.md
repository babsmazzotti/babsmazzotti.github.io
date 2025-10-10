# Sito personale — Babs (Barbara) Mazzotti

Questa cartella contiene i file per pubblicare **gratis** il tuo sito su **GitHub Pages**.

## ✅ Metodo consigliato (user site): `babsmazzotti.github.io`

1. Crea un account (se non l'hai già): https://github.com/signup
2. Clicca **New repository** e come **Repository name** scrivi **`babsmazzotti.github.io`** (tutto minuscolo).
   - Visibility: **Public**
   - *Non* usare template; non serve README iniziale.
3. Entra nel repo e clicca **Add file → Upload files**.
4. Trascina qui dentro i file di questa cartella: `index.html`, `.nojekyll`, `CNAME` (solo se hai un dominio), `.gitignore` (opzionale).
5. Scorri in basso e clicca **Commit changes**.
6. Vai su **Settings → Pages**. In **Build and deployment**, imposta:
   - **Source**: *Deploy from a branch*
   - **Branch**: `main` / **Root**
   - Salva.
7. Attendi 1–2 minuti. Il sito sarà online su:  
   **https://babsmazzotti.github.io**

> Se il nome del tuo account GitHub è diverso, sostituisci di conseguenza (es. `babsthaura.github.io`).

---

## 🟣 Metodo alternativo (project site)

Se vuoi mantenere il tuo nome utente libero o hai già un sito utente, puoi creare un **project site**:

1. Crea un nuovo repo con un nome qualsiasi (es. `sito-babs`).
2. Carica `index.html` (e gli altri file).
3. Vai su **Settings → Pages** e seleziona `main` / Root.
4. Il sito sarà visibile su:  
   `https://<tuo-username>.github.io/sito-babs`

---

## 🌐 Dominio personalizzato (opzionale)

Se acquisti un dominio (es. `babsmazzotti.it`), puoi collegarlo:

1. Modifica il file **CNAME** in questa cartella, inserendo **solo** il tuo dominio (una riga).
2. In **Settings → Pages → Custom domain**, scrivi lo stesso dominio e salva.
3. Nel pannello DNS del tuo registrar crea:
   - Un **CNAME** per `www` → `babsmazzotti.github.io`
   - (Opzionale) Un **ALIAS/ANAME/A record** per root `@` verso gli IP di GitHub Pages:  
     `185.199.108.153` · `185.199.109.153` · `185.199.110.153` · `185.199.111.153`

Attiva **Enforce HTTPS** quando appare l'opzione.

---

## 🧰 Aggiornare il sito

- Modifica il file `index.html` (testo, colori, email, ecc.).
- Fai **Commit** su `main`.  
- GitHub Pages rigenera il sito automaticamente (pochi secondi).

---

## 🧩 File inclusi

- `index.html` — la pagina del sito (one‑page).
- `.nojekyll` — disattiva Jekyll (utile per cartelle con underscore o asset raw).
- `CNAME` — template per dominio personalizzato (compilalo solo se ne hai uno).
- `.gitignore` — opzionale (qui quasi vuoto).

---

_Ultimo aggiornamento: 2025-10-10_

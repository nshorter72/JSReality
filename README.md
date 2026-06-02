# REI Transaction Manager
**JS Reality LLC** — Post-offer pipeline, automated timeline & email templates

Reads Wisconsin purchase agreements (dotloop, Authentisign, any PDF) using Groq and auto-extracts all contract fields.

---

## Deploy to GitHub Pages in 5 minutes

### Step 1 — Get your free Groq API key
1. Go to [console.groq.com/keys](https://console.groq.com/keys)
2. Sign in with your Google account
3. Click **Create API key** → copy it
4. Free tier: generous rate limits, no credit card needed

### Step 2 — Create the GitHub repo
1. Go to [github.com](https://github.com) and sign in (create free account if needed)
2. Click the **+** icon → **New repository**
3. Name it: `rei-transactions` (or anything you want)
4. Set it to **Public**
5. Click **Create repository**

### Step 3 — Upload the file
1. On your new repo page, click **Add file** → **Upload files**
2. Drag and drop `index.html` from this folder
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. In your repo, click **Settings** (top menu)
2. Click **Pages** (left sidebar)
3. Under **Source**, select **Deploy from a branch**
4. Branch: **main** | Folder: **/ (root)**
5. Click **Save**
6. Wait ~60 seconds, then your URL appears:
   `https://YOUR-USERNAME.github.io/rei-transactions/`

### Step 5 — Share with your partner
Send her the URL. She opens it, clicks **⚙ Set API Key**, and enters her own free Groq key (or you can share one key — the free tier is per key, not per user).

---

## How it works

1. Click **⚙ API Key** → paste your Groq key (saves to browser, never leaves your machine)
2. Click **Upload PDF** → drop any Wisconsin purchase agreement
3. Groq reads the contract and extracts all fields automatically
4. Review extraction results, click **Apply to Deal**
5. Hit **Generate Timeline & Emails** for the full deadline schedule
6. Export to `.ics` (imports into Google Calendar, Outlook, Apple Calendar)
7. Copy email templates pre-filled with all deal info
8. Move deals through the **Pipeline** (Active → Under Contract → Clear to Close → Closed)

---

## Works with
- dotloop PDFs ✓
- Authentisign PDFs ✓
- Standard Wisconsin WB-14 forms ✓
- Any text-based purchase agreement ✓
- `.txt` files if PDF is scanned ✓

## Cost
- **$0** — Groq free tier covers ample daily volume
- Each contract extraction = ~1 API call (~8,000 tokens)
- Upgrade to Groq paid if you ever need more volume

---

## Updating the app
When you want to update: edit `index.html`, go back to GitHub, click the file → pencil icon to edit, or upload a new version. GitHub Pages updates within ~30 seconds.

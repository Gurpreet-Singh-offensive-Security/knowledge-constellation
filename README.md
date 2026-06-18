🌌 Knowledge Constellation Explorer

Turn any topic into an interactive "star map" of connected concepts.
Big stars = major ideas, small stars = the granular details (parameters, headers,
mechanisms, edge cases). Click a star to read a plain-language deep explanation,
add your own notes, or expand it to dig even deeper.

Works for IT infrastructure, authentication, security, deep learning, healthcare,
finance — literally anything. Powered by your own free Google Gemini API key.

 Features

    AI-generated concept graphs from a single topic
    Three levels: central → major components → minor details
    Click a star → simple-but-precise explanation
    Double-click (or "Expand") a star → AI generates deeper child nodes
    Notes you can attach to any node (saved in your browser)
    Save / Load a whole constellation (also downloads a .json you can share)
    Drag & drop a saved .json onto the page to reopen it
    Pan, zoom, drag nodes around
    100% static — no backend, no cost to host

 Step 1 — Get a free Gemini API key

    Go to https://aistudio.google.com/apikey
    Sign in with a Google account → Create API key
    Copy the key (it starts with AIza...)
    Paste it into the app's "Gemini API key" box

    The free tier allows a limited number of requests per minute/day. If you see a
    "rate limit" message, just wait ~30 seconds. The app remembers your key in your
    browser so you only paste it once.

 Step 2 — Publish it FREE on GitHub Pages (lifetime)

You don't need to know how to code. Just follow these clicks.
A. Create the repository

    Make a free account at https://github.com
    Click the + (top right) → New repository
    Name it e.g. constellation-explorer
    Set it to Public, then click Create repository

B. Upload the file

    On the new repo page click "uploading an existing file"
    (or Add file → Upload files)
    Drag in index.html (this file from the project)
    Click Commit changes

C. Turn on GitHub Pages

    In the repo go to Settings (top menu)
    Left sidebar → Pages
    Under "Build and deployment" → Source, choose Deploy from a branch
    Branch: main, folder: / (root) → click Save
    Wait ~1 minute, refresh. You'll see:
    "Your site is live at https://YOUR-USERNAME.github.io/constellation-explorer/"

That URL is your permanent, free, shareable tool. 
Anyone can open it in a browser, paste their own free key, and start exploring.

Updating later

Edit index.html directly on GitHub (pencil icon) → Commit. Pages redeploys
automatically in about a minute.

A note on the API key

The key lives only in the user's own browser (localStorage) and is sent straight
to Google's API — it never goes to any server of yours. Each person who uses your
published tool brings their own free key, so it costs you nothing no matter
how many people use it.

Run locally first (optional)

Just double-click index.html — it opens in your browser. No install needed.

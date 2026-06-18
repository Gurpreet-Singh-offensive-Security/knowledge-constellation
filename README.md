<div align="center">

# Knowledge Constellation Explorer

**Type a topic. Watch it explode into a map of stars you can actually explore.**

Big stars are the main ideas. Little stars are the messy details that usually make your brain freeze. Click any of them to get a plain-English explanation, dig deeper, and scribble your own notes.

![Static](https://img.shields.io/badge/Type-Single_HTML_File-1f6feb?style=for-the-badge)
![Cost](https://img.shields.io/badge/Hosting-Free_Forever-3fb950?style=for-the-badge)
![Powered](https://img.shields.io/badge/Powered_by-Gemini-a371f7?style=for-the-badge)
![Backend](https://img.shields.io/badge/Backend-None_Needed-8b949e?style=for-the-badge)

</div>

---

## The 60-second pitch

> You finish a course. You *get* the logic. Then you open a real system — a real request, a real chart, a real workflow — and there are twenty things you've never seen and your brain just goes blank.

This fixes that. Instead of reading about a concept top-to-bottom like a textbook, you **see** it: the core idea in the middle, the major pieces branching out, and every tiny detail hanging off them as its own little star. Your eyes do the remembering.

Works for anything — IT, security, healthcare, finance, biology, whatever you're stuck on.

---

## Textbook vs. this thing

| | The usual way | Constellation Explorer |
|---|---|---|
| **Format** | Wall of text | A living map of stars |
| **Detail** | Buried in paragraphs | Each detail is its own star |
| **Going deeper** | Flip more pages | Double-click → new branch grows |
| **Your notes** | Separate doc you'll lose | Stuck right onto the star |
| **Recall** | Re-read it 3 times | You *picture* where things sit |
| **Cost** | $$ courses | $0 |

---

## How it's wired

```
                 ┌─────────────────┐
                 │   CENTRAL IDEA  │   ← the topic you typed
                 └────────┬────────┘
            ┌─────────────┼─────────────┐
        ┌───┴───┐     ┌───┴───┐     ┌───┴───┐
        │ Major │     │ Major │     │ Major │   ← the main pieces
        └───┬───┘     └───┬───┘     └───────┘
          ┌─┴─┐         ┌─┴─┐
        ┌─┴─┐ ┌┴─┐    ┌─┴─┐ ┌┴─┐
        │ • │ │• │    │ • │ │• │   ← the tiny details (headers,
        └───┘ └──┘    └───┘ └──┘      params, edge cases…)
```

Click a star for the explanation. Double-click it to grow a fresh set of deeper stars off that exact point.

---

## What you can actually do with it

| Action | What happens |
|---|---|
| **Type a topic + Map** | AI builds the whole star map |
| **Click a star** | Plain-English explanation pops up |
| **Double-click a star** | It branches deeper into new stars |
| **Write a note** | Sticks to that star, saved in your browser |
| **Save** | Keeps the map + downloads a file you can share |
| **Drag a saved file in** | Reopens that map instantly |
| **Scroll / drag** | Zoom and rearrange the galaxy |

---

## Get going in 3 steps

**1. Grab a free Gemini key** → https://aistudio.google.com/apikey
Sign in with any Google account, hit *Create API key*, copy the thing that starts with `AIza...`

**2. Open the app** → just double-click `index.html`. That's the whole install.

**3. Paste the key, type a topic, hit Map.** Done.

> The free tier limits how many requests you get per minute. If it asks you to slow down, wait ~30 seconds. The app remembers your key so you only paste it once.

---

## Putting it online for free (and keeping it there)

No coding. Just clicking. Here's the whole journey:

| Step | Where | What to click |
|---|---|---|
| 1 | github.com | **+** (top right) → **New repository** |
| 2 | New repo | Name it `constellation-explorer`, keep it **Public**, **Create** |
| 3 | Repo page | **"uploading an existing file"** → drag in `index.html` → **Commit** |
| 4 | **Settings → Pages** | Source: **Deploy from a branch** |
| 5 | Same screen | Branch **main**, folder **/ (root)** → **Save** |
| 6 | Wait ~1 min, refresh | Grab your live link |

Your link comes out looking like:

```
https://your-username.github.io/constellation-explorer/
```

That's yours for good. Send it to anyone — they open it, paste their own free key, and start exploring.

**Want to change something later?** Click the pencil icon on `index.html` right there on GitHub, edit, commit. It re-publishes itself in about a minute.

---

## "Wait, what about my API key?"

| Worry | Reality |
|---|---|
| Does my key go to some server? | No — there is no server. It lives only in your browser and talks straight to Google. |
| Will it cost me if lots of people use my link? | No. Everyone brings *their own* free key. Your bill stays at $0 no matter the traffic. |
| Do I have to retype it every time? | No — the app saves it locally for you. |

---

<div align="center">

**Built because freezing up in front of a real system is the worst feeling — and a map beats a wall of text every time.**

</div>

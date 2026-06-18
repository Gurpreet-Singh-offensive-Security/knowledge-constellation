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

> Click any panel below to open it.

<details open>
<summary><b>[ + ]  The basics — build &amp; explore</b></summary>

<br>

| Button / action | What happens |
|---|---|
| **→ Map Concept** | AI builds the whole star map from your topic |
| **Click a star** | Plain-English explanation pops up on the right |
| **Double-click a star** | It branches deeper into brand-new detail stars |
| **Write a note** | Sticks to that star, saved in your browser |
| **Scroll / drag** | Zoom and rearrange the galaxy |

</details>

<details>
<summary><b>[ + ]  Saving your work (it's automatic)</b></summary>

<br>

Every time you map or expand, the project **auto-saves** to your browser — so you can close the tab and pick up right where you left off.

```
   [ Map / Expand ]
          |
          v
   auto-saved to browser  ---->  [ ↑ Load ] brings it back
          |
          v
   [ ↓ Save file ]  ---->  a .json on your Desktop / Drive / USB
          |
          v
   drag that .json onto the page  ---->  reopens instantly
```

| Button | What it does |
|---|---|
| **↑ Load** | Brings back your most recent project |
| **↓ Save file** | Downloads a `.json` you can keep anywhere |
| **Drag a `.json` onto the page** | Reopens any saved project instantly |

> First time opening it? You'll get a friendly **welcome** message, not an error.

</details>

<details>
<summary><b>[ + ]  Sharing with your class / group</b></summary>

<br>

Hit **⇗ Share** and the app picks the best route automatically:

```
                        [ ⇗ Share ]
                            |
            ┌───────────────┴───────────────┐
            v                               v
   small / medium project           big research project
            |                               |
            v                               v
   copy a SHARE LINK                 a .json FILE downloads
   paste in class chat               send it (email / drive / chat)
            |                               |
            v                               v
   they click → see your map        they drag it onto the page → opens
```

> **Heads up:** sharing sends a *snapshot* — a frozen copy of your project at that moment. Perfect for handing notes to classmates or prepping a presentation. It's **not** a live Google-Doc-style co-edit (that would need a paid server; this stays 100% free).

</details>

<details>
<summary><b>[ + ]  Starting fresh</b></summary>

<br>

```
   [ ✕ New ]  -->  "Start a brand-new project?"  -->  [ Yes ]  -->  clean board
                            |
                            └──> reminds you to "Save file" first, so
                                 you can never wipe your work by accident
```

Click the red **✕ New** button to wipe the board and begin again.

</details>

---

## Get going in 3 steps

```
   (1) get free key  -->  (2) open index.html  -->  (3) type topic + Map
```

**1. Grab a free Gemini key** → https://aistudio.google.com/apikey
Sign in with any Google account, hit *Create API key*, copy the thing that starts with `AIza...`

**2. Open the app** → just double-click `index.html`. That's the whole install.

**3. Paste the key, type a topic, hit Map.** Done.

> The free tier limits how many requests you get per minute. If it asks you to slow down, wait ~30 seconds. The app remembers your key so you only paste it once.

---

## Putting it online for free (and keeping it there)

<details>
<summary><b>[ + ]  Click for the full step-by-step (no coding, just clicking)</b></summary>

<br>

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

</details>

---

## "Wait, what about my API key?"

<details>
<summary><b>[ + ]  Click — the honest answers to the scary questions</b></summary>

<br>

| Worry | Reality |
|---|---|
| Does my key go to some server? | No — there is no server. It lives only in your browser and talks straight to Google. |
| Will it cost me if lots of people use my link? | No. Everyone brings *their own* free key. Your bill stays at $0 no matter the traffic. |
| Do I have to retype it every time? | No — the app saves it locally for you. |

</details>

---

## If you see an error, don't panic

<details>
<summary><b>[ + ]  Click for the "what's really going on" cheat sheet</b></summary>

<br>

Most "errors" here aren't your fault or the app's — they're just Google's free servers having a busy moment. The app already retries automatically before it ever shows you anything, so usually you won't even notice.

| What it says | What's really going on | What to do |
|---|---|---|
| **"Servers are overloaded / high demand" (503)** | Google's side is momentarily slammed. Totally normal, totally temporary. | The app auto-retries a few times. If it still complains, wait a few seconds and hit the button again, or switch model. |
| **"Sending requests too fast" (429)** | The free tier only allows a handful of requests per minute, and you went over. | Wait ~30 seconds. For heavy expanding, switch to **gemini-2.5-flash-lite** (higher limits). |
| **"API key was rejected"** | Key got mistyped or copied wrong. | Re-copy it from [Google AI Studio](https://aistudio.google.com/apikey). |
| **"Model isn't available"** | That model isn't on your key. | Pick **gemini-2.5-flash** from the dropdown. |
| **"Couldn't reach Google"** | Your internet blinked. | Check your connection and retry. |

> Quick mental model: think of the free API like calling a popular restaurant. Sometimes the line's just busy — you call back in a few seconds and you're in. None of it means anything is broken.

**Going for a giant constellation?** You can expand nodes basically forever, but the only real speed limit is how fast *one free key* is allowed to call Google. Pause a couple seconds between expands (or use the lite model) and you'll sail right past the busy-server hiccups.

</details>

---

<div align="center">

**Built because freezing up in front of a real system is the worst feeling — and a map beats a wall of text every time.**

</div>

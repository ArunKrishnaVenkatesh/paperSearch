# 🧪 Research Meta-Search (Vibe-Coded Edition)

Welcome to the most **vibe-coded academic search tool** you’ll ever find.
No backend. No frameworks. No build tools.
Just straight **HTML + JavaScript + enthusiasm.**

This tiny webpage takes a user’s text input and instantly generates search links across multiple research databases — especially for **tech, engineering, and medical science.**

---

## ✨ What it Does

You type a query like:

```
oral cancer
```

…and boom — you get clickable search links for:

* Google Scholar
* DOAJ Journals
* DOAJ Articles
* OpenAlex Works
* PubMed
* ERIC (Education)
* Semantic Scholar
* medRxiv
* bioRxiv

All using the **exact search URL formats the sites expect.**

---

## 🚀 Why This Exists

Because sometimes you don’t want:

* a server
* OAuth keys
* complicated dashboards
* or a PhD in “wrangling academic APIs”

You want something quick that *just vibes* and gets you to the papers.

This website is that.

---

## 🛠️ How to Run It

1. Download `index.html`.
2. Double-click it.
3. Browser opens.
4. Type things.
5. Click links.
6. Research begins.

No setup. No libraries. **Raw vibes.**

---

## 🧩 How It Works (In Plain English)

* JavaScript grabs whatever text you typed.
* It URL-encodes the query.
* It dynamically injects it into each platform’s required search format.
* It prints links.

That’s it.
That’s the code.

---

## 🧼 Code Philosophy

* **0 dependencies**
* **0 build steps**
* **0 overthinking**
* 100% “What if we just… tried it.”

This is *proof-of-concept energy* — not enterprise architecture.

---

## 📦 Files

```
index.html   # all the magic
```

(There is no second file. Stop looking.)

---

## 🧪 Supported Search Formats

All URLs match live examples from the platforms — including:

* DOAJ JSON search payloads
* OpenAlex `title_and_abstract.search:`
* PubMed `term=`
* Semantic Scholar `sort=relevance`
* medRxiv / bioRxiv double-encoding quirks (`%252B`)

We didn’t fight their formats.
We just accepted their chaos.

---

## 🛑 What This Project Doesn’t Do

* fetch results
* scrape anything
* bypass authentication
* store data
* claim perfection

It just **throws you into research land with style.**

---

## 🔮 Future Improvements (Maybe…)

* checkboxes to pick platforms
* Tailwind UI glow-up
* Node/Python backend
* export link lists
* dark mode for the aesthetic

Or maybe it stays beautifully janky forever.
We’ll see.

---

## 🥂 Credit

Built by a human who said:

> “lol what if we coded this in one sitting”

and then proceeded to do exactly that.

Enjoy the hacks.
Find some research.
**Vibe responsibly.**

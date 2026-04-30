# JSON Formatter & Viewer

A simple, fast JSON formatter I built because most existing tools felt slow, cluttered, or missing small but important features.

👉 https://dev-toolsonline.com/tools/json-formatter

---

## About

This tool is part of a small project called Dev Tools Online — a collection of useful utilities for everyday developer tasks.

The goal is simple: open the page and get things done quickly. No login, no setup, no friction.

If you work with APIs, logs, or messy JSON, this should save you time.

---

## What’s different about it?

There are a lot of JSON formatters out there. Most of them handle the basics, but they often miss the small details that matter when working with real data.

This tool focuses on usability and speed:

- Handles large JSON without freezing  
- Clean UI that stays out of your way  
- Everything runs instantly in the browser  
- No data is stored or sent anywhere  

It also includes features I kept missing in other tools 👇

---

## Features

### 🔍 Search inside JSON
Quickly find keys or values, even in large files.

### 📋 Copy specific objects
Copy individual parts of the JSON instead of the whole thing.  
Useful when working with nested data.

### 🛠 Auto-fix JSON
Fixes common JSON issues automatically so you don’t have to.

### 📂 Upload JSON files
Drop a file and start working immediately.

### 🔗 Auto-paste from links
Paste a URL with JSON and load it directly into the viewer.

### 🌙 Dark mode
Comfortable to use during long sessions.

---

## Core functionality

- Format / beautify JSON  
- Minify JSON  
- Validate structure  
- Syntax highlighting  
- One-click copy  
- Works on desktop and mobile  

---

## Screenshots

### Clean and readable JSON view
![JSON Formatter Main View](./home-page.png)

Formatted JSON with clear structure and syntax highlighting.

---

### Search inside large JSON
![Search Feature](./json-viewer-search.png)

Find keys and values instantly without scrolling.

---

### Copy specific objects
![Copy Options](./copy-options.png)

Copy only what you need.

---

### Dark mode
![Dark Mode](./dark-mode.png)

Better for long sessions and night use.

---

## URL Parameters

You can control the tool directly through the URL. Useful for automation, sharing, and faster workflows.

All parameters can be combined.

### Available parameters

- `?paste=1`  
  Auto-pastes JSON from your clipboard on load.

- `?tab=viewer`  
  Opens the tree viewer (only if JSON is valid).

- `?search=<query>`  
  Pre-fills the search input.

- `?data=<url-encoded-json>`  
  Loads JSON directly from the URL.

---

### Example
?paste=1&tab=viewer&search=id


This will:
- paste JSON from your clipboard  
- switch to viewer mode  
- search for `id`

---

### Notes

- Parameters can be combined in any order  
- `data` must be URL-encoded  
- `tab=viewer` only works with valid JSON  

---

### Use cases

- Share pre-loaded JSON links  
- Debug API responses quickly  
- Bookmark frequent searches  
- Speed up repetitive workflows  

---

## When is this useful?

- Debugging API responses  
- Reading large JSON payloads  
- Extracting specific data  
- Fixing invalid JSON  
- Cleaning JSON before sharing  

---

## About Dev Tools Online

This is part of a growing collection of simple developer tools.

The focus:
- fast  
- easy to use  
- no accounts required  

More tools are coming.

👉 https://dev-toolsonline.com/

---

## Feedback

If something feels off or missing, let me know.  
I’m actively improving this based on real usage.

---

## Support

If you find it useful:
- Star the repo  
- Share it  
- Use it in your workflow  

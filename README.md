# Searchspring Frontend Challenge

This project is a simple search page built using **Vite** and **TypeScript** for the **Searchspring Frontend Challenge**.  
The app interacts with the **Searchspring Search API** to fetch and display product results based on user queries.

---

## 🚀 Tech Stack

- **Vite** — Fast, modern build tool
- **TypeScript** — Type-safe JavaScript
- **React** — UI library for building the search interface
- **CSS / Tailwind (optional)** — For styling (to be updated later)

---

## 🎯 Challenge Overview

The goal is to build a simple search interface using the [Searchspring Search API](https://searchspring.zendesk.com/hc/en-us/sections/115000119223-Search-API).

### Requirements:
- Input box for a **search bar** with a button or "Enter" key trigger.
- Display product results with:
  - `thumbnailImageUrl`
  - `name`
  - `price`
  - `msrp` (crossed out if greater than price)
- Pagination controls (Previous / Next).
- Disable or hide buttons on the first/last page.
- Use the following API parameters:
  - `siteId=scmq7n`
  - `resultsFormat=native`
  - `q` — search query
  - `page` — pagination

---

## 🧩 Example API Endpoint


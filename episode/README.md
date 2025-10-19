# 🎬 Episode Queries

This directory contains GraphQL queries and their respective outputs for retrieving **episode information by ID** and **paginated episode lists**.

---


### 📄 Files (1)

- `episode-id-1.graphql` → Query for episode with **ID 1**  
- `episode-id-1-output.json` → Output for **ID 1**
- `episode-id-2.graphql` → Query for episode with **ID 2**  
- `episode-id-2-output.json` → Output for **ID 2**
- `episode-id-3.graphql` → Query for episode with **ID 3**  
- `episode-id-3-output.json` → Output for **ID 3**
- `episode-id-4.graphql` → Query for episode with **ID 4**  
- `episode-id-4-output.json` → Output for **ID 4**

---


### 📄 Files (2)

- `episodes-page-1.graphql` → Query for episode list on **Page 1**  
- `episodes-page-1-output.json` → Output for **Page 1**
- `episodes-page-2.graphql` → Query for episode list on **Page 2**  
- `episodes-page-2-output.json` → Output for **Page 2**
- `episodes-page-3.graphql` → Query for episode list on **Page 3**  
- `episodes-page-3-output.json` → Output for **Page 3**
- `episodes-page-4.graphql` → Query for episode list on **Page 4**  
- `episodes-page-4-output.json` → Output for **Page 4**

---

## 🧠 Overview

These queries demonstrate:
- Fetching **individual episode details** by ID using the `episode(id: ID!)` field.  
- Fetching **paginated lists of episodes** using the `episodes(page: Int)` field.  
- Selecting fields such as `id`, `name`, `air_date`, and `episode` for structured results.

This provides foundational GraphQL experience with **real-world pagination, filtering, and schema exploration**.

---

## 🔗 API Endpoint

**Rick and Morty GraphQL Endpoint:**  
[`https://rickandmortyapi.com/graphql`](https://rickandmortyapi.com/graphql)


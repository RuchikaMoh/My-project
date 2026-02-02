# Strapi Article Setup

## Overview
This project demonstrates setting up Strapi locally using the official Strapi repository, creating a sample content type, and exposing it via a public API.

## Prerequisites
- Node.js (v18 or v20)
- npm
- Git

## Steps Followed

### 1. Clone the Strapi Repository
```bash
git clone https://github.com/strapi/strapi.git
cd strapi

2. Install Dependencies
npm install

3. Run Strapi Locally
npm run develop

Strapi Admin Panel runs at:
http://localhost:1337/admin

4. Create Content Type

Using the Content-Type Builder, a collection type Article was created with the following fields:

title (Text)

content (Rich Text / Blocks)

published (Boolean)

5. Create Sample Content

A sample Article entry was created in the Content Manager and published.

6. Enable Public API Access

Public role permissions were updated to allow:

find

findOne

7. Verify API
GET http://localhost:1337/api/articles


The endpoint successfully returns article data in JSON format.

Loom Video

(Add Loom link here)


Save the file.

---

### 2️⃣ Commit the README update
Run:

```bash
git status
git add README.md
git commit -m "Update README with Strapi setup steps"
git push

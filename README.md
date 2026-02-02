# Strapi Article Setup
This project includes an Article content type created using Strapi.


## Overview
This project shows how to run Strapi locally, create a sample content type,
and expose it using the public API.

## Prerequisites
- Node.js (v18 or v20)
- npm
- Git

## Steps Followed

### 1. Run Strapi Locally
Install dependencies and start the project:

npm install  
npm run develop  

Admin Panel URL:  
http://localhost:1337/admin

### 2. Create Content Type
A collection type named **Article** was created with the following fields:
- title (Text)
- content (Rich Text / Blocks)
- published (Boolean)

### 3. Create Sample Content
A sample Article entry was added and published from the Content Manager.

### 4. Enable Public API Access
Public role permissions were enabled for:
- find
- findOne

### 5. Verify API
The API endpoint was tested:

GET http://localhost:1337/api/articles

The endpoint returns article data in JSON format.

## Loom Video
(Add Loom link here)

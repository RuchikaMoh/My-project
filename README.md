Strapi Article Setup

Overview  
This project demonstrates setting up Strapi locally using the official Strapi repository,
creating a sample content type, and exposing it via a public API.

Prerequisites
- Node.js (v18 or v20)
- npm
- Git

Steps Followed

1. Clone the Strapi Repository  
git clone https://github.com/strapi/strapi.git  
cd strapi  

2. Install Dependencies  
npm install  

3. Run Strapi Locally  
npm run develop  

Admin Panel:
http://localhost:1337/admin

4. Create Content Type  
Article collection type with fields:
- title (Text)
- content (Rich Text / Blocks)
- published (Boolean)

5. Create Sample Content  
One sample Article entry was created and published.

6. Enable Public API Access  
Permissions enabled:
- find
- findOne

7. Verify API  
GET http://localhost:1337/api/articles

Loom Video  
(Add Loom link here)

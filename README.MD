1. Markdown
2. # RESTful API Activity - [Renzi Kia Danao]
3. ## Best Practices Implementation
4. **1. Environment Variables:**
5. - Why did we put `BASE_URI` in `.env` instead of hardcoding it?
6. - Answer: We put BASE_URI in the .env file so we can easily change it without editing the code. This makes the app more flexible, more secure, and easier to use in different environments like development and production.
7. **2. Resource Modeling:**
8. - Why did we use plural nouns (e.g., `/dishes`) for our routes?
9. - Answer: We use plural nouns because the route represents a collection of resources, not just one item. This follows REST API standards and makes the API easier to understand and consistent.
10. **3. Status Codes:**
11. - When do we use `201 Created` vs `200 OK`?
12. - Why is it important to return `404` instead of just an empty array or a generic error?
13. - Answer: Returning 404 clearly tells the client that the requested resource was not found. This helps users and developers understand the problem quickly and handle errors properly.
14.
15. **4. Testing:**
16. - ![alt text](<Screenshot 2026-01-28 200414.png>)
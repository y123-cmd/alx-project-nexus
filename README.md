# ProDev Backend Engineering – Learnings

This repository documents my key learnings and experiences during the ALX ProDev Backend Engineering program.  
It serves as a personal reference and a guide for future learners who want to understand backend concepts, tools, and best practices.

---

## 1. Core Technologies I Learned

### Python
- General-purpose programming language.  
- I used it mainly for:
  - Writing APIs.  
  - Automating tasks.  
  - Data handling with libraries like `asyncio` and `requests`.  
- Why it stood out: Very beginner-friendly but still powerful in production.

### Django
- Web framework that follows the MVT (Model-View-Template) pattern.  
- Features I found useful:
  - Built-in ORM (no need to write raw SQL).  
  - Authentication system ready to use.  
  - Admin panel for quick debugging.  
- My takeaway: Great for rapid prototyping and still scalable for larger apps.  

### REST APIs
- Learned how to design endpoints for CRUD operations.  
- Example:  
  - `GET /products` → List all products  
  - `POST /products` → Add a new product  
- Strength: Simple and widely used.  

### GraphQL
- Different from REST — you fetch exactly the data you want.  
- Key benefit I liked: avoids “over-fetching” and “under-fetching.”  
- Example: Querying only `name` and `price` of a product instead of the whole object.

### Docker
- Helped me package apps into containers so they work the same everywhere.  
- Useful for:
  - Running the same setup locally and in production.  
  - Making deployments faster.  

### CI/CD
- Learned about automating testing and deployments.  
- Example: Using GitHub Actions for:
  1. Running tests when pushing code.  
  2. Building Docker images.  
  3. Deploying to staging automatically.  

---

## 2. Advanced Concepts I Practiced

### Database Design
- Learned normalization (to remove redundancy) and when to use denormalization (for performance).  
- Example: Used PostgreSQL to design relational schemas with foreign keys.  

### Asynchronous Programming
- Used `async/await` in Python for handling multiple requests at once.  
- Benefit: The server can handle more users without slowing down.  

### Caching
- Learned strategies to reduce database load:  
  - Redis for in-memory caching.  
  - TTL (Time to Live) to expire data automatically.  

---

## 3. Challenges & Solutions
- Challenge: Debugging async code was confusing.  
  - Solution: Added logging and broke tasks into smaller functions.  
- Challenge: Docker builds were failing.  
  - Solution: Optimized Dockerfile with smaller base images.  

---

## 4. Best Practices & Takeaways
- Always write clean, readable code (future me will thank me).  
- Document APIs properly (Swagger helped a lot).  
- Secure sensitive info with environment variables (never hardcode).  
- Test before deployment — saves time later.  

---

## Collaboration
- Worked with other backend learners to test endpoints.  
- Coordinated with frontend learners to ensure APIs returned the data they needed.  

---

## Conclusion
Backend engineering is about balancing **performance**, **scalability**, and **security**.  
This program gave me practical experience with modern tools like Django, Docker, and CI/CD, which I can apply in real-world projects.


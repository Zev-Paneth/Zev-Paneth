### Hi, I'm Zev Paneth

Backend developer, Python. I build and run backend services, and I like hard bugs that cross many layers.

- Currently working on a production geospatial microservice in an air-gapped private cloud
- Daily stack: **Python, FastAPI, Oracle SDE, arcpy, ArcGIS Pro, MongoDB**
- Also: TypeScript, React, Node.js, Git / GitLab CI/CD
- Open to backend roles starting early 2027

**Most of my work is in private repositories** (work code lives on a closed network, and my personal and client projects are private). Some examples of what I build:

- **Geospatial microservice (work)**: a Python service that writes map data into Oracle SDE. Tracked down a recurring data-write failure that used to need manual restarts and fixed it, and added a direct-SQL write path (python-oracledb) next to arcpy.
- **Community platform (private)**: a FastAPI + PostgreSQL backend for a local Jewish community site: synagogues and minyan schedules, Torah classes, schools, businesses, events, and daily zmanim from the Hebcal API with caching and a scheduled cleanup job. Layered routers / services / repositories, 200+ endpoints split into public and admin (JWT), Alembic migrations, 1,000+ pytest tests in GitHub Actions, Docker Compose. React + TypeScript front end with TanStack Query.
- **Vacation-rental site (client, in production)**: Next.js + Payload CMS on Postgres (Neon), deployed on Vercel. A booking-inquiry flow with one Zod schema shared by the form and the server action, rate limiting (Upstash), and email via Resend that rolls back the saved inquiry if sending fails. Schema migrations run from a GitHub Action on every push to `main`, and CI checks that the generated types are in sync.
- **tora-engine (personal)**: a platform for studying Torah texts and building a structured knowledge graph from them: a FastAPI backend, a text reader, and a review page for approving changes before they go in.
- **[status-compressor](https://github.com/Zev-Paneth/status-compressor) (public)**: a self-hosted FastAPI + ffmpeg app that shrinks phone videos for WhatsApp Status, built for a non-technical user and running in production on my VPS.

Code for the private projects is available on request.

Contact: zevpaneth@gmail.com · [LinkedIn](https://www.linkedin.com/in/zev-paneth)

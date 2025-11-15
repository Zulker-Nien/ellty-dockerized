## Quick Start Commands

```bash
# Clone repository
git clone <your-repo-url>
cd ellty-dockerized

# Start with Docker
docker-compose up --build

# Or start manually

# Run pgadmin
## Create database called 
### (synchronized is set to true so you don't have to run any migrations)
ellty-db

# Terminal 1: Backend
cd ellty2-backend
npm install
npm run start:dev

# Terminal 2: Frontend
cd ellty2
npm install
npm run dev


```

Access: http://localhost:3000
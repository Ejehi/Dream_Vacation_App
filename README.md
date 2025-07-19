# Dream Vacation App

## Run the entire app


- docker-compose builds all three images.
- Runs frontend, backend, and database containers.
- Containers talk to each other using service names (db).

## Access your app


- Open http://localhost:3000 (React frontend)
- Backend API runs at http://localhost:5001
- PostgreSQL runs on localhost:5433 (internally named db)

## Push images to Docker Hub

- The images are now publicly available on Docker Hub
# Dream Vacation App

## GitHub Actions CI/CD pipeline

<img width="1710" height="988" alt="Screenshot 2025-08-03 at 14 54 49" src="https://github.com/user-attachments/assets/6c9b80dc-cf65-460a-a7b0-9c3b3cfe0e8e" />



<img width="1710" height="987" alt="Screenshot 2025-08-03 at 14 58 58" src="https://github.com/user-attachments/assets/a5e49b26-3527-4f17-9b93-6ea465ae92dc" />


GitHub runs this workflow automatically by using your saved secrets to log in securely to dockerhub.

## Run the entire app

<img width="1710" height="1107" alt="docker-build-up" src="https://github.com/user-attachments/assets/1a9c86c3-25de-4ae9-b076-f03878c969ac" />

- docker-compose builds all three images.
- Runs frontend, backend, and database containers.
- Containers talk to each other using service names (db).

## Access your app

<img width="1710" height="1107" alt="Screenshot 2025-07-19 at 03 20 44" src="https://github.com/user-attachments/assets/786382ca-5c16-4f47-b3c5-8b65bccd3a06" />

- Open http://localhost:3000 (React frontend)
- Backend API runs at http://localhost:5001
- PostgreSQL runs on localhost:5433 (internally named db)

## Push images to Docker Hub
<img width="1710" height="1107" alt="push-to-docker-hub" src="https://github.com/user-attachments/assets/48e44484-fff4-47f9-8d1d-a68a50ec6537" />

<img width="1710" height="990" alt="dream-vacation-on-dub-1" src="https://github.com/user-attachments/assets/d2759ae2-1e89-47a4-93db-b536649a7f1c" />

<img width="1710" height="990" alt="dream-vacation-on-hub-2" src="https://github.com/user-attachments/assets/bbcc96fc-e10f-49d5-94a0-2f14fca7feae" />


- The images are now publicly available on Docker Hub

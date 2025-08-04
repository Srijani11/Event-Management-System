#  FunFusion - Event Management System

## About

**FunFusion** is a full-stack event management system where users can explore and book events while administrators manage event listings, view bookings, and handle user feedback.

**This project is built using:**
-  **React.js + Html + CSS + Axios** for the frontend
-  **Node.js + Express** for the backend API
-  **MySQL** for the database
---

## Features

### User Side
- Browse upcoming events
- Book tickets with name, age, gender, and quantity
- View success confirmation after booking
- Submit feedback after event

### Admin Side
- Add new events (Tech, Music, Food, Art,Theatre)
- View event list with total ticket stats
- Manage all user bookings
- View and delete user feedback

---

### Main API Endpoints
### Events

| Method | Endpoint     | Description              |
|--------|--------------|--------------------------|
| GET    | `/events`    | Get all events           |
| POST   | `/events`    | Add new event (admin)    |

###  Bookings

| Method | Endpoint     | Description              |
|--------|--------------|--------------------------|
| GET    | `/bookings`  | Get all bookings (admin) |
| POST   | `/bookings`  | Book tickets (user)      |

###  Feedback

| Method   | Endpoint          | Description                   |
|----------|-------------------|-------------------------------|
| GET      | `/feedback`       | Get all feedback (admin)      |
| POST     | `/feedback`       | Submit feedback (user)        |
| DELETE   | `/feedback/:id`   | Delete feedback by ID (admin) |

---


##  Tech Stack

| Layer       | Tech Used             |
|-------------|------------------------|
| Frontend    | React.js, Html, CSS |
| Backend     | Node.js, Express.js    |
| Database    | MySQL                  |
| Deployment  | Localhost / Your host  |


----

##  Screenshots
<img width="1920" height="1080" alt="Screenshot (411)" src="https://github.com/user-attachments/assets/3d5ac98f-7c27-4eab-a209-bd79a426737a" />
<img width="1920" height="1080" alt="Screenshot (413)" src="https://github.com/user-attachments/assets/2dd6fbd9-cee0-479d-8fc1-359abac34774" />
<img width="1920" height="1080" alt="Screenshot (417)" src="https://github.com/user-attachments/assets/f3fae626-e142-4e2a-b908-333652ccc433" />
<img width="1920" height="1080" alt="Screenshot (414)" src="https://github.com/user-attachments/assets/a7cebd22-f564-4938-b174-593356c4dd71" />
<img width="1920" height="1080" alt="Screenshot (412)" src="https://github.com/user-attachments/assets/5897e869-8c8d-4381-a8b4-9433685dbecc" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/d644455b-c75c-4e63-ac4b-70e057233cc8" />
<img width="1920" height="1080" alt="Screenshot (416)" src="https://github.com/user-attachments/assets/a569d161-9c88-4f4b-af29-8ab2df452483" />






---


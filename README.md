# taxi-clone
(user based only) get location - (select)destination - price by distance(km*x+arr.size());

 Taxi-Core — Uber-like Ride Sharing System

 Project Description

 Core Features

 1. Authentication System
	•	Secure login

➕ Additional:
	•	Role-based access (Driver / Rider)
	•	Profile management

⸻

🧍 2. Rider Features
	•	Request a trip (pickup + destination)
	•	Real-time driver tracking (live location)
	•	Trip history
	•	Rate & review drivers
  
⸻

📍 3. Real-Time System
	•	WebSocket-based communication
	•	Live driver location updates
	•	Instant trip status updates

⸻


🧱 System Architecture

Frontend (Angular)
        ↓
REST API (Django + DRF)
        ↓
Real-Time Layer (Django Channels + Redis)
        ↓
Database (PostgreSQL + PostGIS)


⸻

🛠️ Technologies Used

Backend:
	•	Django
	•	Django REST Framework (DRF)
	•	Django Channels (WebSockets)
	•	PostgreSQL + PostGIS
	•	Redis
	•	Celery

Frontend:
	•	Angular

Other:
	•	Stripe (Payments)
	•	Docker (Deployment)

⸻

⚙️ Key Functional Modules

📦 Trip Management
	•	Create trip request
	•	Assign driver
	•	Track trip status:

REQUESTED → ACCEPTED → IN_PROGRESS → COMPLETED




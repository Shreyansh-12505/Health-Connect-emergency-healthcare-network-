# Healthcare Emergency Connect

A hackathon-focused ambulance dispatch prototype with patient booking, real-time driver requests, live simulated tracking, hospital availability, priority sorting, and polished glassmorphism UI.

## Demo Accounts

- Patient: `patient@test.com` / `123456`
- Driver: `driver@test.com` / `123456`

## Quick Start

```bash
npm run install:all
npm run dev
```

Frontend: http://localhost:5173  
Backend: http://localhost:8080

## Data

The hackathon demo uses fake seeded data. No MongoDB setup is required.

For deployment, leave `MONGODB_URI` empty or unset. The backend will use JSON/in-memory demo data automatically.

## Winning Demo Flow

1. Open the patient dashboard and submit an emergency request.
2. Open the driver dashboard in another tab or browser.
3. Watch the request arrive instantly through Socket.io.
4. Driver accepts the request.
5. Patient receives instant status update.
6. Open tracking to show ambulance movement, ETA, priority, and nearby hospitals.

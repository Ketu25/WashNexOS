# WashNexOS

A pickup & drop-off scheduling platform for a laundromat business. Customers can
schedule pickup/drop-off of clothes within a geofenced service area; laundromat
staff manage incoming requests through an admin dashboard.

## Project Structure

```
WashNexOS/
├── backend/       # FastAPI app (API, geofence logic, auth)
├── frontend/      # Next.js app (customer + admin portals)
├── terraform/
│   ├── dev/       # Dev infrastructure
│   └── prod/      # Production infrastructure
└── README.md
```

## Branches

- `main` — production, protected, deploy-only
- `dev` — active development, all feature work merges here first

## Tech Stack

- **Backend:** FastAPI, PostgreSQL
- **Frontend:** Next.js, Tailwind CSS
- **Infra:** AWS, Terraform
- **Geocoding:** Mapbox / Google Geocoding API
- **Notifications:** Twilio / AWS SNS

## Build Phases

1. DB schema + project scaffolding
2. Auth (customer + admin roles)
3. Geocoding + geofence validation
4. Address management
5. Booking flow (pickup/dropoff scheduling)
6. Order status / history
7. Admin dashboard
8. Status update actions
9. Notifications
10. Admin-editable settings (service radius, hours)
11. Polish + edge cases
12. Pilot with real users

## Local Setup

_To be filled in once backend/frontend scaffolding is added._

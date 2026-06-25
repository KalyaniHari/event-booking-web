# Event Booking Web

React + TypeScript frontend for an event booking platform. Users can browse and
book events, organizers can create and manage their events, and admins get an
overview of users, events, bookings, and payments.

> Backend API: [event-booking-api](https://github.com/KalyaniHari/event-booking-api)

## Features

- User registration and login
- Browse events and book a spot
- Payment page for confirming bookings
- "My Bookings" view for users
- Organizer dashboard to create and manage events
- Admin dashboard overview

## Tech Stack

- React 18 + TypeScript (Create React App)
- React Router for navigation
- Axios for API requests
- `react-modal`, `moment`

## Pages / Routes

| Route | Page |
|-------|------|
| `/` | Login / landing |
| `/register` | Sign up |
| `/dashboard` | User event dashboard |
| `/my-bookings` | User's bookings |
| `/payment/:bookingId` | Payment for a booking |
| `/organizer-dashboard` | Organizer event management |
| `/admin-dashboard` | Admin overview |

## Getting Started

1. **Install dependencies**
   ```bash
   npm install
   ```

2. **Start the backend** ([event-booking-api](https://github.com/KalyaniHari/event-booking-api))
   so the frontend has an API to call (default `http://localhost:5000`).

3. **Run the app**
   ```bash
   npm start
   ```
   Opens <http://localhost:3000>.

## Available Scripts

- `npm start` — run in development mode
- `npm test` — run tests
- `npm run build` — production build into `build/`

## License

Released under the [MIT License](LICENSE).

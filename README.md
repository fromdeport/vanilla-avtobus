🚌 AVTOBUS.UZ — Y2K Online Booking System

Retro-styled online bus ticket booking system built with pure HTML, CSS & JavaScript.






✨ About the Project

AVTOBUS.UZ is a fully interactive demo bus booking system inspired by early 2000s web design aesthetics.

It combines:

🎨 Neon Y2K UI

💾 LocalStorage-based seat persistence

🎟️ Dynamic seat selection

💳 Simulated payment system

📄 Ticket generation & history view

All written in a single HTML file.
No frameworks. No backend. Just raw browser power.

🚀 Features
🔍 Bus Search

Choose departure and destination cities

Select travel date

View available bus schedules

See real-time seat availability

💺 Seat Selection

40-seat grid layout

Visual seat states:

🟢 Available

🟣 Taken

🟡 Selected

Seat availability saved in localStorage

💳 Payment (Demo Mode)

Passenger information form

Card details input (simulation only)

Animated processing screen

Booking confirmation with unique ID

🎫 My Tickets

View all booked tickets

Booking ID

Passenger details

Seats

Total cost

Booking timestamp

🛠 Tech Stack

HTML5

CSS3 (Retro / Y2K styling)

Vanilla JavaScript

LocalStorage API

No external libraries.
No frameworks.
No build tools.
Just open and run.

📦 How to Run

Download the HTML file.

Open it in your browser.

That’s it.

No server required.

🧠 How Seat Persistence Works

Seats are stored per:

booked_seats_{busId}_{date}

Example:

booked_seats_2_2026-03-05

This ensures:

Different buses have separate seat data

Different dates have separate seat data

Seat reservations persist after page refresh

🎨 Design Philosophy

Inspired by:

Early 2000s web portals

Neon glow UI

Pixel fonts

Animated marquees

“Best viewed in 800x600” era

Features include:

Animated star background

Blinking headers

Gradient buttons

Ridge / groove borders

Press Start 2P & VT323 fonts

⚠️ Important Notes

Payment system is demo only

Card data is not processed or validated securely

Tickets are stored only in memory (except seat locking)

Refreshing page resets ticket history (not seat locks)

🔮 Possible Improvements

Backend integration (Node.js / Express)

Real payment API integration

Database for bookings

Authentication system

Admin panel

Mobile optimization

API-based bus data

📸 Preview

Aesthetic highlights:

Neon green text on dark blue background

Retro scrolling banner

Animated booking confirmation

Arcade-style buttons

📜 License

This project is for educational and demo purposes.

👨‍💻 Author

Built as a front-end demo booking system with nostalgic Y2K energy.

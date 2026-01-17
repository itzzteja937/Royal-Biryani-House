🍛 Royal Biryani House

Royal Biryani House is a modern, responsive food ordering web application designed for local restaurants.
It allows customers to browse dishes, add items to a cart, and place lunch orders seamlessly via WhatsApp, while the backend stores orders securely in Google Sheets using Google Apps Script.

🚀 Live Features

🧾 Interactive food menu with categories (Veg, Non-Veg, Best Sellers, Starters)

🛒 Real-time cart management with quantity controls

⏰ Automatic ordering time window (10:00 AM – 11:50 PM)

❌ Out-of-stock & Coming-Soon product handling

📲 WhatsApp order confirmation with auto-generated Order ID

📊 Google Sheets integration for order storage

📱 Fully responsive UI for mobile & desktop

🔒 Basic validation for customer name & mobile number

🖥️ Tech Stack

Frontend

HTML5
CSS3 (Flexbox, animations, responsive design)
JavaScript (Vanilla JS)

Backend / Integration

Google Apps Script (as REST API)
Google Sheets (order database)
WhatsApp Click-to-Chat API


🛒 How Ordering Works

1. User selects food items and quantity
2. Cart updates in real time
3. Ordering allowed only during active time window
4. User enters name & mobile number
5. Order is:
       Saved to Google Sheets
       Assigned a unique Order ID
       Sent to restaurant via WhatsApp automatically

⏱️ Ordering Time Logic

Orders are automatically disabled outside: 10:00 AM – 11:50 PM

🔐 Validation & Safety

Prevents empty cart checkout
Mobile number validation (10 digits, non-zero start)
Double-submit prevention for orders
Disabled actions for out-of-stock items

🌱 Future Enhancements

Online payment integration (UPI / Razorpay)
Admin dashboard for order management
Login & order history
Live order status tracking
Cloud backend (Firebase / Node.js)

📍 Location & Contact

Delivery Location:
Rajapushpa Paradigm, ISB Road, Financial District,
Nanakramguda, Hyderabad, Telangana – 500032

📞 Contact: +91 8309451136

📄 License

This project is created for learning and local business use.
You are free to modify and enhance it.
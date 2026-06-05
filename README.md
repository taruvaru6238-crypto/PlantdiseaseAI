# PlantdiseaseAI
🌱 Project: AI-Powered Plant Care Reminder with Disease ID
Project Overview
Build a website where users can track their houseplants, set care reminders (watering, fertilizing, pruning), and identify plant diseases by uploading photos. Perfect for plant lovers in Bengaluru's climate.

Core Features (MVP - Minimum Viable Product)
1. Plant Profile Dashboard
Add plants with:

Plant name (dropdown or search from database)

Photo upload

Category (Indoor, Outdoor, Succulent, Herb, etc.)

Purchase/adoption date

Location in home (Living room, Bedroom, Balcony)

View all plants in grid or list view

Quick stats: Total plants, plants needing care today

2. Smart Care Reminders
Automated reminders based on plant type:

Watering schedule (every 3 days, weekly, etc.)

Fertilizing schedule (monthly, seasonal)

Pruning reminders

Repotting alerts

Browser notifications or email reminders

Mark tasks as complete with one click

3. Disease Identification (Simple Version)
Upload photo of sick plant (leaf with spots, yellowing, wilting)

User selects symptoms from checklist:

Yellow leaves

Brown spots

Wilting

Pest visible

Mold/fungus

Get common diagnoses and treatment suggestions

Practice: Form handling, image upload, conditional logic

4. Care History Log
Track when you last watered, fertilized, pruned

View care timeline for each plant

Add notes (e.g., "New leaves growing!", "Moved to brighter spot")

5. Plant Database
Pre-populated list of 50+ common houseplants

Each plant has:

Care level (Beginner, Intermediate, Advanced)

Watering frequency

Light requirements

Ideal temperature range

Common problems

Advanced Features (Add Later)
AI Disease Detection: Integrate with AI API (like PlantNet or custom ML model) to analyze uploaded photos

Bengaluru Climate Integration: Adjust care schedules based on local weather (rainy season = less watering)

Plant Community: Share photos, get advice from other users

Plant Swap Marketplace: Trade cuttings/seeds with local plant lovers

Barcode/QR Scanner: Scan plant nursery tags to auto-add plant details

Growth Progress Photos: Timelapse gallery showing plant growth over months

WhatsApp Notifications: Send reminders via WhatsApp API

Tech Stack Recommendation
Component	Technology
Component	Technology
Frontend	HTML, CSS, JavaScript (or React for better state management)
Backend	Firebase (easiest for beginners) OR Node.js + Express
Database	Firebase Firestore (NoSQL, real-time)
Authentication	Firebase Auth (email, Google login)
Image Storage	Firebase Storage OR Cloudinary
Notifications	Firebase Cloud Messaging (browser push) OR EmailJS
Weather API	OpenWeatherMap API (for Bengaluru climate integration)
Hosting	Firebase Hosting OR Netlify

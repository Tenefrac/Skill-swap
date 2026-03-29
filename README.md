# Skill-swap

DONE IN LARAVEL
QUALITY EDUCATION SDG
Many students need help with academic, creative, and technical tasks such as tutoring, thesis editing, graphic design, and coding. However, many cannot afford to pay professionals. At the same time, many students already have valuable skills but have no organized and trusted system to offer or exchange them. Most students rely on Facebook groups or chat messages, which are unstructured, unreliable, and inefficient.

techstack:
Laravel frame work
PHP
CCS
HTML

TARGET USERS:
- Students
- Freelancers
- Professionals
- Hobbyists
- Anyone with a skill to offer or a service needed

CORE CONCEPT:
Users can offer services (e.g., tutoring, coding, graphic design, writing, video editing) or request help. Instead of paying money, users earn credits by helping others and spend credits to request services.

CORE FEATURES:

1. User Authentication
   - Register using email or social login
   - Optional identity verification (ID upload or badges)

2. User Profile
   - Skills, bio, availability
   - Portfolio uploads (images, links, files)
   - Ratings and reviews
   - Skill level tags (Beginner, Intermediate, Expert)

3. Skill Marketplace
   - Post service offers
   - Post service requests
   - Categories: Academic, Creative, Technical, Lifestyle, Business

4. AI Matching System
   - Match users based on:
     - Skills and needs
     - Availability
     - Ratings
     - Location (optional)
     - Past transactions

5. Credit/Token System
   - Earn credits by completing tasks
   - Spend credits to request services
   - Transaction history
   - Optional bonus credits for new users

6. Chat System
   - Real-time messaging
   - File/image sharing
   - Notifications

7. Rating & Review System
   - Mutual rating after each transaction
   - Builds trust and reputation

8. Trust & Safety
   - Report users
   - Dispute system
   - Moderation tools

UI/UX REQUIREMENTS:
- Clean, modern, minimal design
- Inspired by Notion and marketplace apps
- Easy navigation for all types of users

PLATFORM:
- Responsive web app
- Optional mobile app

GOAL:
Create a structured, reliable platform where anyone can exchange skills efficiently without needing money.




🧰 1. Install Requirements

Before installing Laravel, you need:

✅ PHP (8.1 or higher)
Install via:
XAMPP (easy all-in-one)
or standalone PHP
✅ Composer (VERY IMPORTANT)
Composer is required to install Laravel
Download: https://getcomposer.org/

👉 Check if installed:

php -v
composer -V
🚀 2. Install Laravel

Open Command Prompt / Terminal, then run:

composer create-project laravel/laravel myApp

👉 This will:

Create a folder named myApp
Install Laravel inside it
📂 3. Go to Your Project
cd myApp
▶️ 4. Run Laravel

Start the built-in server:

php artisan serve

You should see something like:

Server running on http://127.0.0.1:8000

👉 Open in browser:

http://127.0.0.1:8000
🛠️ 5. (Optional) Use XAMPP Instead

If you're using XAMPP:

Move your project to:

htdocs/
Start Apache in XAMPP

Open:

http://localhost/myApp/public

# DazzleGuru Affiliate Marketing Platform

Welcome to DazzleGuru, your premier destination for online courses and affiliate marketing. Our platform offers a range of educational courses designed to cater to various skill levels, from beginners to advanced professionals. Inspired by successful platforms like BizGurukul, LeadsGuru, and Millionaire Track, DazzleGuru provides a comprehensive suite of tools and resources to help you succeed.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Course Plans](#course-plans)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Authentication**: Secure sign-up and login system with password recovery.
- **Comprehensive Course Offerings**: Diverse courses categorized into Starter, Pro, Elite, and Ultimate plans.
- **Affiliate Dashboard**: Track referrals, commissions, and performance metrics.
- **Payment Gateway Integration**: Secure transactions with Stripe and PayPal.
- **Responsive Design**: Optimized for mobile, tablet, and desktop viewing.
- **Progress Tracking**: Monitor course progress and receive certifications.

## Technologies Used

- **Frontend**:
  - HTML5
  - CSS3 (Bootstrap for responsive design)
  - JavaScript (jQuery for dynamic content)

- **Backend**:
  - Node.js with Express.js / Python with Flask or Django (for server-side logic)
  - Firebase Authentication or Custom Authentication System
  - MongoDB / MySQL (for data storage)

- **Payment Integration**:
  - Stripe API / PayPal API (for secure payments)

- **Deployment**:
  - GitHub Pages (for static site hosting)
  - Netlify / Heroku (for dynamic content)

## Installation

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/dazzleguru-affiliate-platform.git
    cd dazzleguru-affiliate-platform
    ```

2. **Install dependencies**:
   For Node.js and Express.js:
    ```bash
    npm install
    ```

   For Python and Flask:
    ```bash
    pip install -r requirements.txt
    ```

3. **Configure environment variables**:
   Create a `.env` file in the root directory with the following variables:

    ```bash
    # For Node.js
    PORT=3000
    MONGODB_URI=your_mongodb_connection_string
    STRIPE_SECRET_KEY=your_stripe_secret_key

    # For Flask
    FLASK_APP=app.py
    FLASK_ENV=development
    DATABASE_URL=your_database_url
    STRIPE_SECRET_KEY=your_stripe_secret_key
    ```

4. **Start the application**:
   For Node.js:
    ```bash
    npm start
    ```

   For Flask:
    ```bash
    flask run
    ```

5. **Access the website**:
   Open your browser and visit `http://localhost:3000` (for Node.js) or `http://127.0.0.1:5000` (for Flask).

## Usage

### User Authentication
- Register and log in to access course materials and the affiliate dashboard.
- Manage your profile and reset your password if needed.

### Course Plans

**Starter Plan**
- **Canva Master**: Introductory design skills, accessible for beginners.
- **Google Ads**: Entry-level marketing knowledge.
- **Website Designing**: Basic website building skills.
- **Stock Analysis**: Foundational understanding of market trends.

**Pro Plan**
- **Digital Marketing**: Comprehensive marketing strategies beyond Google Ads.
- **Python**: Intermediate programming skills for practical applications.
- **Graphic Designing**: Expanded design skills beyond Canva.
- **Power BI**: Basic data visualization and analysis skills.

**Elite Plan**
- **Cybersecurity**: Advanced understanding of digital protection.
- **Adobe Photoshop**: Professional-level graphic design and editing.
- **Artificial Intelligence**: Cutting-edge technology and machine learning.
- **2D Animation**: Advanced animation techniques.
- **Data Science**: In-depth data analysis and machine learning.

**Ultimate Plan**
- Access to **all the above courses**.

### Affiliate Dashboard
- Monitor your referrals, track earnings, and access marketing resources.

### Payments
- Purchase courses securely using Stripe or PayPal.

## Project Structure

Here's an overview of the project's structure:

```plaintext
dazzleguru-affiliate-platform/
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── img/
│   │   └── logo.png
│   └── js/
│       └── main.js
├── views/
│   ├── index.html
│   ├── about.html
│   ├── contact.html
│   ├── dashboard.html
│   └── courses.html
├── routes/
│   ├── auth.js
│   ├── courses.js
│   └── dashboard.js
├── models/
│   ├── user.js
│   ├── course.js
│   └── affiliate.js
├── config/
│   ├── database.js
│   └── stripe.js
├── .env
├── .gitignore
├── package.json
├── README.md
└── server.js (or app.py for Flask)

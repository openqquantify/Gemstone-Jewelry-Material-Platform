# OpenQQuantify E-Commerce-Gemstone-Jewelry-Material-Shopping-Platform

![Flask](https://img.shields.io/badge/Flask-2.3.2-green)
![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.0-blueviolet)
![Stripe](https://img.shields.io/badge/Stripe-5.5.0-blue)
![Web3](https://img.shields.io/badge/Web3-6.4.0-orange)

Discover our cutting-edge e-commerce platform designed for buying and selling precious gemstones and luxury jewelry, where merchant support meets secure payments and advanced Web3 integration. This state-of-the-art digital commerce solution seamlessly blends blockchain technology with traditional secure payment gateways, offering an online marketplace that caters to the modern jewelry enthusiast and savvy merchant alike. Our platform features robust SEO-optimized designs, responsive mobile compatibility, and user-friendly interfaces that elevate digital sales in the competitive jewelry and gemstones market. With integrated smart contracts, cryptocurrency payment options, and real-time inventory updates, we are redefining the future of secure, innovative commerce, ensuring every transaction is safe, efficient, and tailored to meet modern consumer demands in the luxury e-commerce space.

## ✨ Features

### User System
- 🔐 Secure authentication (register/login/logout)
- 👤 User profiles with roles (buyer/merchant)
- 🔑 Password hashing with PBKDF2-SHA256

### Merchant Portal
- 🏪 Create merchant profiles
- 📦 Product management dashboard
- 🖼️ Image upload with auto-thumbnails

### Marketplace
- 🔍 Advanced search by material/attributes
- 🛒 Shopping cart functionality
- 💳 Stripe & crypto payment options
- 📱 Fully responsive design

### Product Listings
- 💎 Detailed gemstone specifications:
  - Material composition
  - Weight/carat measurements
  - Color/clarity grades
  - Country of origin

## 🛠️ Tech Stack

### Backend
- Python 3.10+
- Flask framework
- SQLAlchemy ORM
- Stripe API integration
- Web3.py for crypto payments

### Frontend
- Bootstrap 5.3
- Font Awesome 6
- Custom CSS animations
- Vanilla JavaScript

### Database
- SQLite (development)
- MySQL (production)

## 🚀 Quick Start

### Prerequisites
- Python 3.10+
- pip package manager
- MySQL (for production)

## 📁 Project Structure

```bash
gemstone-jewelry-material-platform/
├── app/                          # Main application directory
│ ├── static/                     # Static files (CSS, JS, images)
│ ├── templates/                  # HTML templates
│ │ ├── base.html                 # Base template
│ │ ├── dashboard.html            # Dashboard page
│ │ ├── home.html                 # Home page
│ │ ├── merchant_profile.html     # Merchant profile page
│ │ └── search.html               # Search page
│ ├── uploads/                    # File uploads directory
│ ├── auth/                       # Authentication module
│ ├── payments/                   # Payments module
│ ├── products/                   # Products module
│ ├── init.py                     # Package initialization
│ ├── config.py                   # Configuration settings
│ ├── forms.py                    # Form definitions
│ ├── models.py                   # Database models
│ ├── routes.py                   # Application routes
│ ├── utils.py                    # Utility functions
│ └── run.py                      # Application entry point
├── requirements.txt              # Python dependencies
├── LICENSE                       # License file
└── README.md                     # Project documentation
```

### Key Directories Explained:

1. **`app/`** - Core application package
   - `routes.py`: Organized using Flask Blueprints (auth, main, products)
   - `models.py`: Contains all SQLAlchemy models (User, Merchant, Product)
   - `utils/`: Modular utilities for payments, auth, and file handling

2. **`static/`** - Frontend assets
   - Designed with mobile-first responsive approach
   - Vanilla JavaScript (no jQuery dependency)

3. **`templates/`** - Jinja2 templates
   - Uses template inheritance (`base.html`)
   - Modular partials for reusable components
   - Organized by feature (auth, products, payments)

4. **Configuration**
   - `config.py`: Centralized configuration
   - `.env.example`: Template for environment variables
   - `requirements.txt`: Pinned dependencies

### Best Practices:
- **Separation of Concerns**: Clear division between routes, models, and templates
- **Modular Design**: Features split into logical components
- **Security**: Uploads stored outside static folder
- **Scalability**: Ready for MySQL migration in production

### Installation

# Clone repository
git clone https://github.com/openqquantify/Gemstone-Jewelry-Material-Platform.git
cd gemstone-marketplace

# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set up environment
cp .env.example .env

## Team Leaders
- Paul Savluc - CEO & Founder
- Adam Karabin - COO
- Havard Lillebo - CFO

## Engineers/Developers 
- Roberta-Andreea Popescu 

## Connect With Us!
- Paul Savluc, CEO & Founder, LinkedIn: https://www.linkedin.com/in/paul-savluc/
- OpenQQuantify, LinkedIn: https://www.linkedin.com/company/openqquantify/
- Tomorrow's AI, LinkedIn: https://www.linkedin.com/company/tomorrows-ai/

### We Are Looking for Team Members, Investors, Sponsors, and Partners! 
Reach out to us!
We handle consulting and contracts as well!

### Star, Share, and Follow Us! Support us! 
We make it possible for people around the world to learn about electronics, embedded systems, robotics, supply chain, and 3d simulations and autonomous systems.
We do more than that! Find out about all the domains under OpenQQuantify!

![output](https://github.com/user-attachments/assets/09930e68-fbb1-4d7b-8bcf-7890e12744ec)

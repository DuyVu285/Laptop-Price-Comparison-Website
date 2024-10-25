# Price Comparison Website

A feature-rich price comparison website that allows users to search for products, view prices from multiple sources, and find the best deals. Includes a user side with search and shopping cart, and an admin dashboard for inventory and order management.

## Features
- **User**: Product search with similarity matching, shopping cart, order details, recently viewed products.
- **Admin**: Inventory and order management, product filtering, deduplication for accuracy.

## Technologies Used
- **Frontend**: Angular, Ant Design (NgZorro)
- **Backend**: NestJS, MongoDB, GridFS (image storage)
- **Web Scraping**: Puppeteer for product data

## Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB (local Compass)
-
### Installation
1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/Price-Comparison-Website.git
   cd Price-Comparison-Website
2. **Install Dependencies**:

    # Backend
    cd Price-Comparison-Website-Server \
    npm install
    cd Price-Comparison-Website-Scrape-Server \
    npm install
    # Frontend
    cd Price-Comparison-Website-Client \
    npm install
4. **Set up Environment Variables**:
   DATABASE_URL=<your_mongodb_connection_string>

### Run The Application
1. **Backend**:
  cd Price-Comparison-Website-Server \
  nest start
  cd Price-Comparison-Website-Scrape-Server \
  nest start
2. **Frontend**:
  cd Price-Comparison-Website-Client \
  ng server
3.**Access**:
   Visit http://localhost:4200 in your browser.   

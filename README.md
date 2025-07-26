<h1 align="center">E-Commerce Store 🛒</h1>

![Demo App](/frontend/public/screenshot-for-readme.png)


-   🚀 Project Setup
-   🗄️ MongoDB & Redis Integration
-   💳 Stripe Payment Setup
-   🔐 Robust Authentication System
-   🔑 JWT with Refresh/Access Tokens
-   📝 User Signup & Login
-   🛒 E-Commerce Core
-   📦 Product & Category Management
-   🛍️ Shopping Cart Functionality
-   💰 Checkout with Stripe
-   🏷️ Coupon Code System
-   👑 Admin Dashboard
-   📊 Sales Analytics
-   🎨 Design with Tailwind
-   🛒 Cart & Checkout Process
-   🔒 Security
-   🛡️ Data Protection
-   🚀Caching with Redis
-   ⌛ And a lot more...

### Setup .env file

```bash
PORT=5000
MONGO_URI=your_mongo_uri

UPSTASH_REDIS_URL=your_redis_url

ACCESS_TOKEN_SECRET=your_access_token_secret
REFRESH_TOKEN_SECRET=your_refresh_token_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

STRIPE_SECRET_KEY=your_stripe_secret_key
CLIENT_URL=http://localhost:5173
NODE_ENV=development
```

### Run this app locally

```shell
npm run build
```

### Start the app

```shell
npm run start
```

## Project Overview
This is a full-featured E-Commerce platform built with the MERN stack (MongoDB, Express.js, React.js, Node.js). The application provides a robust shopping experience with features like user authentication, product management, shopping cart functionality, and secure payment processing.

### Key Features
- **User Authentication**: Secure signup/login with JWT and refresh tokens
- **Product Management**: Add, edit, and delete products with image upload
- **Shopping Cart**: Real-time cart updates and persistence
- **Payment Processing**: Secure checkout with Stripe integration
- **Admin Dashboard**: Complete control over products, orders, and users
- **Performance**: Redis caching for improved response times
- **Security**: Protected routes and data validation

### Tech Stack
- **Frontend**: React.js, TailwindCSS, Redux
- **Backend**: Node.js, Express.js
- **Database**: MongoDB, Redis
- **File Storage**: Cloudinary
- **Payment**: Stripe
- **Authentication**: JWT

### API Documentation
The API includes the following main endpoints:
- `/api/auth` - Authentication routes
- `/api/products` - Product management
- `/api/orders` - Order processing
- `/api/cart` - Shopping cart operations
- `/api/admin` - Admin-only operations

### Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

### License
This project is licensed under the MIT License.

### Installation Guide
1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/mern-ecommerce.git
   cd mern-ecommerce
   ```

2. **Install Dependencies**
   ```bash
   # Install backend dependencies
   npm install
   
   # Install frontend dependencies
   cd frontend
   npm install
   ```

### Development Setup
1. **Start Redis Server**
   - Ensure Redis is installed and running
   - Update .env with your Redis configuration

2. **Database Setup**
   - Create MongoDB cluster
   - Add connection string to .env
   - Initial data will be seeded automatically

3. **Start Development Servers**
   ```bash
   # Start backend (from root directory)
   npm run dev
   
   # Start frontend (from frontend directory)
   npm run dev
   ```

### Testing
```bash
# Run backend tests
npm run test

# Run frontend tests
cd frontend && npm run test
```

### Feature Details

#### Authentication System
- JWT-based authentication
- Refresh token rotation
- Password reset functionality
- OAuth integration ready

#### Admin Features
- Complete order management
- User management system
- Sales analytics dashboard
- Inventory tracking
- Bulk product operations

#### Shopping Features
- Real-time cart updates
- Wishlist functionality
- Order tracking
- Review & rating system
- Related products
- Advanced search & filters

#### Technical Features
- Redis caching for improved performance
- Image optimization
- Rate limiting
- Error logging
- API documentation with Swagger
- Responsive design

### Deployment
The application can be deployed using:
- Docker containers
- Cloud platforms (AWS, GCP, Azure)
- Traditional VPS
- PaaS solutions like Heroku

### Performance Optimization
- Image lazy loading
- Redis caching
- CDN integration
- Code splitting
- Bundle optimization

### Security Measures
- CSRF protection
- XSS prevention
- Rate limiting
- Input sanitization
- Secure headers
- Data encryption

For more detailed documentation, please visit our [Wiki](https://github.com/yourusername/mern-ecommerce/wiki)

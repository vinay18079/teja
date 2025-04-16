# Vintage Clothing E-Commerce Website

A modern e-commerce website for Vintage clothing brand, featuring a responsive design, product catalog, shopping cart, and UPI payment integration.

## Features

- Responsive design for all devices
- Product catalog with filtering options
- Shopping cart functionality
- UPI payment integration
- Modern and clean user interface
- Product categories: T-Shirts, Shirts, and Innerwear
- Size options: S, M, L, XL, XXL

## Technologies Used

- React.js
- React Router
- Styled Components
- Axios
- Razorpay (for UPI payments)

## Setup Instructions

1. Clone the repository:
```bash
git clone <repository-url>
cd vintage-clothing
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

## Payment Integration

The website uses Razorpay for UPI payments. To enable payments:

1. Sign up for a Razorpay account
2. Get your API keys
3. Update the payment configuration in the Checkout component

## Project Structure

```
src/
  ├── components/
  │   └── Header.js
  ├── pages/
  │   ├── Home.js
  │   ├── Products.js
  │   ├── Cart.js
  │   └── Checkout.js
  ├── App.js
  └── index.js
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details. 
# 🍕 Food Delivery Web Application

A modern, responsive food delivery platform built with React.js that provides users with an intuitive interface to browse menus, manage their cart, and place orders seamlessly.

## 🚀 Features

- **Dynamic Menu Browsing**: Interactive food categories with filtering capabilities
- **Real-time Cart Management**: Add/remove items with live quantity updates
- **User Authentication**: Secure login/signup modal system
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Smooth Navigation**: Client-side routing with React Router
- **Interactive UI**: Modern animations and hover effects
- **State Management**: Centralized cart and user state with React Context

## 🛠️ Tech Stack

**Frontend:**
- React.js 18+
- React Router Dom (Client-side routing)
- React Context API (State management)
- React Hooks (useState, useContext)
- CSS3 (Custom styling with animations)

**Architecture:**
- Component-based architecture
- Functional components with hooks
- Centralized state management
- Modular CSS organization

## 📱 Pages & Components

### Pages
- **Home**: Hero section, menu exploration, and food display
- **Cart**: Shopping cart management and item review
- **Place Order**: Checkout and order placement

### Key Components
- **Navbar**: Navigation with active states and cart indicator
- **FoodItem**: Interactive food cards with add/remove functionality
- **LoginPopup**: Modal-based authentication system
- **Header**: Hero section with call-to-action
- **Footer**: Contact information and links

## 🎨 Key Functionalities

1. **Menu Exploration**: Browse food items by categories with smooth filtering
2. **Cart Operations**: Add items, modify quantities, and remove products
3. **Authentication Flow**: Toggle between login and signup modes
4. **Responsive Navigation**: Mobile-friendly menu with active link highlighting
5. **Visual Feedback**: Loading states, hover effects, and smooth transitions

## 🚦 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/food-delivery-app.git
cd food-delivery-app
```

2. Install dependencies
```bash
npm install
```

3. Start the development server
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

## 📁 Project Structure

```
src/
├── components/
│   ├── Navbar/
│   ├── Header/
│   ├── FoodItem/
│   ├── LoginPopup/
│   └── Footer/
├── pages/
│   ├── Home/
│   ├── Cart/
│   └── PlaceOrder/
├── context/
│   └── StoreContext.jsx
├── assets/
└── App.jsx
```

## 🔧 Configuration

The application uses React Context for state management. Key configurations include:
- Cart state management
- User authentication state
- Food items and categories
- Navigation state tracking

## 📊 Performance Features

- **Component Optimization**: Functional components with efficient re-rendering
- **State Management**: Centralized context to avoid prop drilling
- **CSS Animations**: Smooth transitions and fade-in effects
- **Responsive Images**: Optimized food item imagery
- **Code Splitting**: Route-based code splitting with React Router

## 🔮 Future Enhancements

- [ ] Backend API integration
- [ ] Payment gateway implementation
- [ ] Order tracking functionality
- [ ] User profile management
- [ ] Restaurant management system
- [ ] Real-time notifications
- [ ] Multi-language support

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


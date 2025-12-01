# GroceryCatalogue
Complete grocery catalogue app with cart and search
# 🛒 Grocery Catalogue App

A beautiful, fully-featured grocery shopping application built with React Native and Expo. Features tab-based navigation, product listings, search functionality, and interactive shopping cart with persistent state.

![React Native](https://img.shields.io/badge/React_Native-0.72.0-61DAFB?style=for-the-badge&logo=react&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-49.0.0-000020?style=for-the-badge&logo=expo&logoColor=white)
![Platform](https://img.shields.io/badge/Platforms-iOS%20%7C%20Android%20%7C%20Web-4BC51D?style=for-the-badge)

## 📱 App Preview

| Home Screen | Product Search | Shopping Cart |
|-------------|----------------|---------------|
| <img src="https://images.unsplash.com/photo-1568702846914-96b305d2aaeb?w=250" width="180"> | <img src="https://images.unsplash.com/photo-1445282768818-728615cc910a?w=250" width="180"> | <img src="https://images.unsplash.com/photo-1563636619-e9143da7973b?w=250" width="180"> |

## ✨ Features

- 🍎 **Four Product Categories**: Fruits, Vegetables, Dairy, and Bakery
- 🛒 **Interactive Shopping Cart**: Add, remove, and manage quantities
- 🔍 **Smart Search**: Real-time product filtering with persistent search terms
- 💾 **Persistent State**: Cart items and search history saved using localStorage
- 📱 **Tab Navigation**: Smooth bottom navigation between categories
- 🎨 **Beautiful UI**: Modern design with high-quality product images
- 📱 **Cross-Platform**: Works on iOS, Android, and Web
- ⚡ **Fast Performance**: Optimized React Native components

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or newer)
- npm or yarn
- Expo CLI

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ewuwise/GroceryCatalogue.git
   cd GroceryCatalogue
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npx expo start
   ```

4. **Run on your preferred platform**
   ```bash
   # iOS Simulator (macOS only)
   npx expo start --ios

   # Android Emulator
   npx expo start --android

   # Web Browser
   npx expo start --web
   ```

## 📁 Project Structure

```
GroceryCatalogue/
├── App.js                 # Main application component
├── package.json           # Dependencies and scripts
├── babel.config.js        # Babel configuration
├── navigation/
│   └── TabNavigator.js    # Bottom tab navigation setup
└── screens/
    ├── FruitsScreen.js    # Fruits product listings
    ├── VegetablesScreen.js # Vegetables product listings
    ├── DairyScreen.js     # Dairy product listings
    └── BakeryItemsScreen.js # Bakery product listings
```

## 🛠 Technologies Used

- **Frontend Framework**: React Native 0.72.0
- **Development Platform**: Expo SDK 49
- **Navigation**: React Navigation v6
- **State Management**: React Context API + localStorage
- **Styling**: React Native StyleSheet
- **Icons**: Font Awesome Icons

## 🎯 Key Features

### 🔍 Smart Search & Filtering
- Real-time product search across all categories
- Persistent search terms (saved in localStorage)
- Visual tab indicators showing categories with results
- "No results" messaging for better UX

### 🛒 Advanced Cart Management
- Add items with quantity selection
- Persistent cart state across browser sessions
- Real-time cart count and total calculation
- Quantity adjustment and item removal
- Empty cart state with helpful messaging

### 📱 User Experience
- Smooth animations and transitions
- Responsive design for all screen sizes
- Toast notifications for user feedback
- Professional color scheme and typography
- Intuitive tab-based navigation

## 📦 Dependencies

### Core Dependencies
```json
{
  "expo": "~49.0.0",
  "react": "18.2.0",
  "react-native": "0.72.0",
  "@react-navigation/native": "^6.1.0",
  "@react-navigation/bottom-tabs": "^6.5.0",
  "react-native-screens": "~3.22.0",
  "react-native-safe-area-context": "4.6.0"
}
```

## 🎮 How to Use

### Browse Products
1. Open the app to see the FreshMart home screen
2. Navigate between categories using the bottom tabs:
   - 🍎 **Fruits**: Handpicked, extra juicy fruits
   - 🥦 **Vegetables**: Fresh vegetables from farmers
   - 🥛 **Dairy**: Fresh dairy products daily
   - 🍞 **Bakery**: Freshly baked goodies

### Search Products
1. Use the search bar at the top to find specific products
2. Watch as products filter in real-time
3. See visual indicators on tabs with matching products
4. Your search term persists across page reloads

### Manage Cart
1. Click "Add to Cart" on any product (optionally adjust quantity first)
2. View cart by clicking the cart icon in the header
3. Adjust quantities or remove items in the cart sidebar
4. Proceed to checkout when ready

## 🔧 Customization

### Adding New Products
Edit the product arrays in each screen file:

```javascript
// In any screen component
const products = [
  { 
    id: 25,
    name: 'New Product', 
    price: 5.99, 
    image: 'https://example.com/image.jpg',
    description: 'Product description'
  },
  // ... more products
];
```

### Modifying Styles
Update the styles in the component files:

```javascript
const styles = StyleSheet.create({
  // Modify colors, spacing, or overall theme
  container: {
    backgroundColor: '#your-color',
  },
  productCard: {
    // Custom card styles
  }
});
```

## 🌐 Demo

Try the live demo: [Expo Snack Demo](https://snack.expo.dev/@your-username/grocery-catalogue)

## 🤝 Contributing

We welcome contributions! Please feel free to submit issues, feature requests, or pull requests.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Product images provided by [Unsplash](https://unsplash.com)
- Icons from [Font Awesome](https://fontawesome.com)
- Built with [Expo](https://expo.dev) and [React Native](https://reactnative.dev)

## 📞 Support

If you have any questions or need help with setup, please open an issue in the GitHub repository.

---

<div align="center">

**Made with ❤️ and React Native**

⭐ Star this repo if you found it helpful!

</div>
```

This README provides:

1. **Professional header** with badges and preview images
2. **Clear feature list** highlighting the cart and search functionality
3. **Easy setup instructions** for developers
4. **Project structure** overview
5. **Detailed feature explanations** with screenshots
6. **Customization guide** for extending the app
7. **Contributing guidelines** for open-source collaboration
8. **Professional formatting** with emojis and sections


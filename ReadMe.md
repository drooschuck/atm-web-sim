# 🏧 ATM Web Simulator - JavaScript Edition 

A realistic web-based ATM (Automated Teller Machine) simulator with full banking functionality, built with HTML, CSS, and JavaScript.

![ATM Simulator Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML-5-orange) ![CSS](https://img.shields.io/badge/CSS-3-blue) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

## 🌟 Features

### Customer Functions
- **Secure Login**: PIN-based authentication with masked input
- **Balance Inquiry**: View current account balance
- **Cash Withdrawal**: Withdraw money in multiples of £10
- **PIN Management**: Change PIN with secure verification process
- **Transaction History**: View personal withdrawal history
- **Input Validation**: Comprehensive error handling and validation

### Admin Functions
- **Admin Access**: Special admin mode with password protection
- **Transaction Monitoring**: View all customer transactions
- **System Management**: Admin-specific interface

### Technical Features
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Real-time Validation**: Instant feedback on user inputs
- **Transaction Logging**: In-memory transaction storage
- **Interactive UI**: Physical keypad simulation with sound-like feedback
- **Error Handling**: Comprehensive validation and user-friendly error messages
- **Security Features**: PIN masking and secure authentication

## 🚀 Live Demo

[JavaScript Cash Point Simulator](https://cpsim.netlify.app/)

## 📁 Project Structure

```
atm-simulator/
├── index.html          # all in one (HTML,styles.css, script.js)   
├── styles.css          # CSS styling and animations (Separate for best practice)
├── script.js           # JavaScript functionality  (Separate for best practice)
├── README.md           # Project documentation
└── screenshots/        # Demo images (optional)
```

## 🛠️ Installation & Setup

### Option 1: Direct Download
1. Download all files to a local folder
2. Open `index.html` in your web browser
3. Start using the ATM simulator!

### Option 2: Clone Repository
```bash
git clone https://github.com/yourusername/atm-simulator.git
cd atm-simulator
# Open index.html in your browser or use a local server
```

## 🎮 How to Use

### Customer Access
1. **Login**: Enter PIN `1234` and press `ENT`
2. **Main Menu**: Choose from available options:
   - A. View Balance
   - B. Withdraw Cash
   - C. Change PIN
   - D. View Transactions
   - E. Exit

### Admin Access
1. **Login**: Enter password `4321` and press `ENT`
2. **Admin Menu**: Access administrative functions:
   - View all customer transactions
   - System monitoring

### Navigation
- **Keypad**: Use number buttons to enter PINs and amounts
- **Function Buttons**: 
  - `← Back`: Return to previous screen
  - `Menu`: Go to main menu
  - `Clear`: Clear current input
  - `Help`: Get contextual help

## 🔧 Configuration

Default settings can be modified in `script.js`:

```javascript
// Default configuration
let currentPin = '1234';        // Customer PIN
let balance = 123.45;           // Starting balance
const adminPassword = '4321';   // Admin password
```

## 🌐 Deployment

### Netlify Deployment
1. Fork this repository
2. Connect your GitHub account to Netlify
3. Deploy directly from GitHub
4. Get instant HTTPS URL

### Manual Deployment
1. Upload all files to any web server
2. Ensure `index.html` is in the root directory
3. Access via your domain

### GitHub Pages
1. Push code to GitHub repository
2. Enable GitHub Pages in repository settings
3. Select source branch (usually `main`)

## 🔐 Security Features

- **PIN Masking**: PINs are displayed as asterisks
- **Input Validation**: All inputs are validated before processing
- **Session Management**: Secure login/logout functionality
- **Error Handling**: Prevents unauthorized access attempts

## 📱 Browser Compatibility

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🎨 Customization

### Styling
Modify `styles.css` to change:
- Color schemes
- Fonts and typography
- Layout and spacing
- Animations and transitions

### Functionality
Modify `script.js` to:
- Add new transaction types
- Change validation rules
- Implement new features
- Modify user interface behavior

## 🐛 Known Issues & Limitations

- Transaction data is stored in browser memory only (resets on page reload)
- No backend integration (purely client-side)
- No real banking connectivity (simulation only)

## 🔄 Future Enhancements

- [ ] Persistent storage with localStorage
- [ ] Multiple account support
- [ ] Transaction receipts
- [ ] Sound effects
- [ ] Multi-language support
- [ ] Backend API integration
- [ ] Mobile app version

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [@yourusername](https://github.com/yourusername)
- Website: [yourwebsite.com](https://yourwebsite.com)

## 🙏 Acknowledgments

- Inspired by real ATM interfaces
- Built with modern web technologies
- Designed for educational and demonstration purposes

## 📞 Support

If you encounter any issues or have questions:
1. Check the [Issues](https://github.com/yourusername/atm-simulator/issues) page
2. Create a new issue with detailed description
3. Contact the author directly

---

**⭐ Star this repository if you found it helpful!**

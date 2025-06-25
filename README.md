# 🔐 Safe Notes - Secure Note Management App

A modern, secure note-taking application built with React that allows users to store and manage their notes, passwords, and sensitive information with encryption and passkey protection.

![Safe Notes](https://img.shields.io/badge/React-18.0.0-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

## ✨ Features

### 🔒 **Security Features**
- **4-Digit Passkey Protection**: Secure access with encrypted passkey
- **Local Storage Encryption**: All data is encrypted before storage
- **Session Management**: Automatic logout for security
- **Data Privacy**: No data sent to external servers

### 📝 **Note Management**
- **Create & Edit Notes**: Rich text support with formatting
- **Search Functionality**: Quick search through all notes
- **Date Tracking**: Automatic timestamp for each note
- **Delete & Update**: Full CRUD operations

### 🔑 **Password Management**
- **Encrypted Storage**: Passwords stored with encryption
- **Secure Display**: Masked password viewing
- **Easy Management**: Add, edit, and delete passwords

### 🎨 **Modern UI/UX**
- **Responsive Design**: Works on desktop and mobile
- **Page-Specific Themes**: Unique color schemes for each section
- **Smooth Animations**: Modern hover effects and transitions
- **Intuitive Navigation**: Easy-to-use interface

## 🚀 Quick Start

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/SakshamShri/FINAL-PROJECT-ELEVATE_LABS-PRIVACY-FOCUSED-NOTES-APP.git
   cd FINAL-PROJECT-ELEVATE_LABS-PRIVACY-FOCUSED-NOTES-APP
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 📱 Usage Guide

### First Time Setup
1. **Set Passkey**: Enter a 4-digit passkey when prompted
2. **Remember Your Passkey**: This is required to access your data
3. **Start Using**: Begin creating notes and storing passwords

### Daily Usage
1. **Enter Passkey**: Use your 4-digit passkey to unlock
2. **Choose Section**: Select Notes or Passwords
3. **Manage Content**: Add, edit, or delete your items
4. **Lock When Done**: Use the lock button to secure your data

## 🛠️ Technology Stack

- **Frontend**: React 18.0.0
- **Routing**: React Router DOM 6.3.0
- **Storage**: IndexedDB (local browser storage)
- **Styling**: Modern CSS with CSS Variables
- **Icons**: Font Awesome
- **Build Tool**: Create React App

## 📁 Project Structure

```
Safe-Notes/
├── public/
│   ├── index.html
│   ├── manifest.json
│   └── images/
├── src/
│   ├── pages/
│   │   ├── Home.js          # Main dashboard
│   │   ├── Notes.js         # Notes management
│   │   └── Passwords.js     # Password management
│   ├── App.js              # Main app component
│   ├── App.css             # Global styles
│   └── index.js            # App entry point
├── package.json
└── README.md
```

## 🎨 Design Features

### Color Themes
- **Home Page**: Warm yellow theme with orange accents
- **Notes Page**: Cool blue theme with purple accents  
- **Passwords Page**: Elegant purple theme with pink accents

### Modern UI Elements
- **Gradient Backgrounds**: Beautiful color transitions
- **Card-Based Layout**: Clean, organized content display
- **Hover Effects**: Interactive button and card animations
- **Responsive Grid**: Adaptive layout for all screen sizes

## 🔧 Available Scripts

- `npm start` - Runs the app in development mode
- `npm build` - Builds the app for production
- `npm test` - Launches the test runner
- `npm eject` - Ejects from Create React App (one-way operation)

## 🔒 Security Details

### Encryption Method
- **Custom Algorithm**: Proprietary encryption for data security
- **Character Substitution**: Advanced character mapping
- **Local Processing**: All encryption happens in the browser

### Data Storage
- **IndexedDB**: Modern browser database for reliable storage
- **No Cloud Storage**: All data stays on your device
- **Automatic Backup**: Data persists between sessions

## 🌟 Key Features

### ✨ **Smart Search**
- Real-time search through notes and passwords
- Instant filtering and results
- Case-insensitive search

### 📱 **Mobile Responsive**
- Optimized for all device sizes
- Touch-friendly interface
- Adaptive layouts

### 🎯 **User Experience**
- Intuitive navigation
- Clear visual feedback
- Smooth transitions and animations

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **React Team** for the amazing framework
- **Font Awesome** for the beautiful icons
- **Create React App** for the development setup

## 📞 Support

If you have any questions or need help:
- Create an issue on GitHub
- Check the documentation
- Review the code comments

---

**Made with ❤️ for secure note management**

*Remember: Your security is our priority. Keep your passkey safe!*

# 🐋 BELUGAS NFT Marketplace

A modern, decentralized NFT marketplace built on the XRP Ledger (XRPL) that allows users to create, mint, buy, sell, and trade unique digital assets.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Pages Overview](#pages-overview)
- [Technology Stack](#technology-stack)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

BELUGAS is a comprehensive NFT marketplace that leverages the power of the XRP Ledger to provide fast, secure, and cost-effective NFT trading. The platform offers a complete ecosystem for digital asset creation, minting, and trading with a focus on user experience and security.

### Key Highlights

- **XRP Ledger Integration**: Built on XRPL for fast transactions and low fees
- **Modern UI/UX**: Clean, responsive design with intuitive navigation
- **Wallet Integration**: Seamless wallet connection with QR code support
- **Collection Management**: Create and manage NFT collections easily
- **Real-time Analytics**: Track portfolio performance and market trends

## ✨ Features

### Core Functionality
- 🎨 **NFT Creation**: Upload and create unique digital assets
- 💎 **Minting**: Mint NFTs on the XRP Ledger
- 🛒 **Marketplace**: Buy, sell, and trade NFTs
- 👛 **Wallet Integration**: Connect XRP wallets securely
- 📊 **Dashboard**: Portfolio management and analytics
- 🔍 **Search & Discovery**: Find NFTs and collections easily

### User Experience
- 📱 **Responsive Design**: Works on desktop, tablet, and mobile
- 🎭 **Collection Categories**: Art, Music, Video, Sports, Fashion
- 📈 **Market Statistics**: Real-time price updates and volume tracking
- 🔒 **Security**: Blockchain-backed ownership verification
- ⚡ **Fast Transactions**: XRPL's quick confirmation times

## 📄 Pages Overview

### 1. **Home Page** (`index.html`)
- **Purpose**: Main landing page and marketplace overview
- **Features**:
  - Hero section with rotating background images
  - Featured NFT collections showcase
  - Multiple collection categories (Top, Trending, Mint, Oldest, Upcoming)
  - Category filter buttons
  - Wallet connection with QR code modal
  - Navigation to all major sections

### 2. **Explore Page** (`explore.html`)
- **Purpose**: Platform introduction and service showcase
- **Features**:
  - Platform statistics (NFTs created, active users, XRP traded)
  - How BELUGAS works explanation
  - Service cards (Marketplace, Collection Creation, Analytics)
  - Featured collections display
  - Platform benefits and features overview

### 3. **Dashboard** (`dashboard.html`)
- **Purpose**: User portfolio and wallet management
- **Features**:
  - Wallet address display
  - XRP balance tracking
  - Total NFTs count
  - NFT grid display with search functionality
  - Tab system (NFTs, Offers, History)
  - Refresh and disconnect wallet options

### 4. **Create Collection** (`create-collection.html`)
- **Purpose**: NFT collection creation interface
- **Features**:
  - Collection creation form
  - Asset upload functionality
  - Metadata configuration
  - Minting options and settings

### 5. **All Collections** (`collections.html`)
- **Purpose**: Browse all available NFT collections
- **Features**:
  - Grid layout of all collections
  - Search functionality
  - Collection cards with images and metadata
  - Direct links to individual collection views

### 6. **Collection View** (`collection-view.html`)
- **Purpose**: Detailed view of individual NFT collections
- **Features**:
  - Collection statistics (Floor price, Items, Volume, Holders, Listed)
  - Progress bar showing minting status
  - Large collection image display
  - Minted NFTs grid
  - Individual NFT details and metadata
  - Mint functionality

## 🛠 Technology Stack

### Frontend
- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with responsive design
- **JavaScript**: Interactive functionality and wallet integration
- **Vanilla JS**: No framework dependencies for lightweight performance

### Blockchain
- **XRP Ledger (XRPL)**: Underlying blockchain for NFT transactions
- **XRP**: Native cryptocurrency for transactions and fees

### Assets
- **Images**: High-quality collection images and backgrounds
- **QR Codes**: Wallet connection integration
- **Icons**: Emoji-based and custom icons

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- XRP wallet (XUMM, Ledger, or other XRPL-compatible wallet)
- Basic understanding of NFTs and blockchain technology

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/belugas-nft-marketplace.git
   cd belugas-nft-marketplace
   ```

2. **Open the Project**
   - Simply open `index.html` in your web browser
   - Or use a local development server for better experience

3. **Start Local Server** (Optional but Recommended)
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

4. **Access the Application**
   - Open your browser and navigate to `http://localhost:8000`
   - The application will load with all features available

### Running the Application

1. **Direct File Opening**
   - Double-click `index.html` to open in your default browser
   - Navigate through pages using the navigation menu

2. **Local Server** (Recommended)
   - Start a local server in the project directory
   - Access via `http://localhost:8000`
   - Better for testing wallet connections and API calls

## 📁 Project Structure

```
BELUGAS NFT Markeekplace/
├── 📄 HTML Files
│   ├── index.html              # Main landing page
│   ├── explore.html            # Platform exploration page
│   ├── dashboard.html          # User dashboard
│   ├── create-collection.html  # Collection creation
│   ├── collections.html        # All collections view
│   └── collection-view.html    # Individual collection view
│
├── 🎨 CSS Files
│   ├── index.css               # Main page styles
│   ├── explore.css             # Explore page styles
│   ├── dashboard.css           # Dashboard styles
│   ├── create-collection.css   # Collection creation styles
│   ├── collections.css         # Collections grid styles
│   └── collection-view.css     # Collection detail styles
│
├── 🖼️ Asset/
│   ├── collection/             # NFT collection images
│   │   ├── download (1).jpg
│   │   ├── download (2).jpg
│   │   └── ... (more images)
│   ├── QR/                     # QR code assets
│   │   └── download.png
│   └── Background images       # Hero section backgrounds
│
└── 📖 README.md               # This file
```

## 💡 Usage

### For Users

1. **Browse Collections**
   - Visit the home page to see featured collections
   - Use the "All Collections" page to browse everything
   - Search for specific collections using the search bar

2. **Connect Wallet**
   - Click "Connect Wallet" button
   - Scan QR code with your XRP wallet
   - View your portfolio in the dashboard

3. **View Collections**
   - Click on any collection card to view details
   - See collection statistics and minted NFTs
   - Access individual NFT information

4. **Create Collections** (Creators)
   - Navigate to "Create Collection"
   - Upload your digital assets
   - Configure metadata and settings
   - Mint your NFTs

### For Developers

1. **Customization**
   - Modify CSS files for styling changes
   - Update HTML structure as needed
   - Add JavaScript functionality for enhanced features

2. **Integration**
   - Connect to XRPL APIs for real data
   - Implement wallet connection logic
   - Add backend services for data persistence

## 🔧 Development

### Adding New Features

1. **New Pages**
   - Create new HTML file
   - Add corresponding CSS file
   - Update navigation links

2. **Styling Changes**
   - Modify existing CSS files
   - Test responsiveness across devices
   - Ensure consistency with design system

3. **Functionality**
   - Add JavaScript for interactive features
   - Integrate with XRPL APIs
   - Implement wallet connection logic

### Best Practices

- **Responsive Design**: Ensure all pages work on mobile devices
- **Performance**: Optimize images and minimize file sizes
- **Accessibility**: Follow WCAG guidelines for inclusive design
- **Security**: Implement proper wallet connection security measures

## 🤝 Contributing

We welcome contributions to improve BELUGAS NFT Marketplace!

### How to Contribute

1. **Fork the Repository**
2. **Create a Feature Branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Make Your Changes**
4. **Test Thoroughly**
5. **Submit a Pull Request**

### Contribution Guidelines

- Follow existing code style and formatting
- Add comments for complex functionality
- Test changes across different browsers
- Update documentation as needed

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and questions:
- Create an issue in the GitHub repository
- Contact the development team
- Check the documentation for common solutions

## 🔮 Roadmap

### Upcoming Features
- [ ] Advanced search and filtering
- [ ] Social features and comments
- [ ] Mobile app development
- [ ] Advanced analytics dashboard
- [ ] Multi-chain support
- [ ] Auction functionality
- [ ] Royalty distribution system

### Version History
- **v1.0.0**: Initial release with basic marketplace functionality
- **v1.1.0**: Added collection creation and management
- **v1.2.0**: Enhanced dashboard and analytics

---

**Built with ❤️ for the XRP Ledger community**

*BELUGAS NFT Marketplace - Where Digital Art Meets Blockchain Innovation* 
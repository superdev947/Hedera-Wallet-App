# Hedera Wallet App (Web23 Super Wallet)

A comprehensive React Native mobile wallet application for the Hedera network, featuring multi-language support, NFT management, domain services, and smart wallet capabilities.

## 📱 Features

- **Wallet Management**
  - Create and recover wallets using mnemonic phrases
  - Secure password protection
  - Private key and secret phrase management
  - Multi-wallet support

- **Transaction Features**
  - Send and receive HBAR
  - Token swapping capabilities
  - Gift token functionality
  - Transaction history tracking

- **NFT Support**
  - Create and manage NFTs
  - NFT gallery and viewing
  - Post NFT to social platforms
  - Media attachment support

- **Domain Services**
  - Domain management and lookup
  - Domain detail viewing
  - Domain section navigation

- **Smart Wallet**
  - Smart wallet setup and configuration
  - Balance top-up functionality
  - Web2 configuration integration

- **Social Features**
  - Post creation with NFTs
  - Comment system
  - Social token setup
  - Community engagement tools

- **Security & Settings**
  - Connection management for dApps
  - Contact management
  - Terms & privacy viewing
  - Support contact system
  - Multi-language support (10+ languages)

- **Discovery**
  - Dashboard compass for exploring dApps
  - Site connection capabilities
  - Integrated browser features

## 🛠️ Tech Stack

- **Framework**: React Native 0.71.6
- **Language**: TypeScript 4.8.4
- **Navigation**: React Navigation 6.x (Stack Navigator)
- **State Management**: Context API
- **Styling**: NativeWind (Tailwind CSS for React Native)
- **Internationalization**: i18next with 10+ language support
- **UI Components**: Custom component library
- **Testing**: Jest

## 🌍 Supported Languages

- English
- Arabic
- German (Deutsch)
- Spanish (Español)
- French (Français)
- Hindi (हिन्दी)
- Italian (Italiano)
- Japanese (日本語)
- Mandarin (中文)
- Polish (Polski)

## 📋 Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (v14 or higher)
- npm or yarn
- React Native CLI
- Xcode (for iOS development on macOS)
- Android Studio (for Android development)
- CocoaPods (for iOS dependencies)

## 🚀 Getting Started

### Installation

1. Clone the repository:
```bash
git clone https://github.com/superdev947/Hedera-Wallet-App.git
cd Hedera-Wallet-App
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Install iOS dependencies (macOS only):
```bash
cd ios
pod install
cd ..
```

### Running the App

#### Android
```bash
npm run android
# or
yarn android
```

#### iOS
```bash
npm run ios
# or
yarn ios
```

### Development

Start the Metro bundler:
```bash
npm start
# or
yarn start
```

## 🧪 Testing

Run the test suite:
```bash
npm test
# or
yarn test
```

## 📁 Project Structure

```
Hedera-Wallet-App/
├── src/
│   ├── api/                    # API integration layer
│   ├── assets/                 # Images, icons, and static resources
│   │   ├── icons/
│   │   └── png/
│   ├── components/             # Reusable UI components
│   │   ├── mnemonic-box/
│   │   ├── web23-button/
│   │   ├── web23-input/
│   │   ├── web23-modal/
│   │   └── ... (20+ components)
│   ├── config/                 # App configuration
│   ├── i18n/                   # Internationalization
│   │   └── resource/           # Language translations
│   ├── layouts/                # Layout components
│   │   └── screen/
│   ├── navigation/             # Navigation configuration
│   ├── screens/                # Screen components
│   │   ├── dashboard/          # Dashboard screens
│   │   │   ├── discover/
│   │   │   ├── domain/
│   │   │   ├── history/
│   │   │   ├── nft/
│   │   │   ├── setting/
│   │   │   └── wallet/
│   │   ├── home/              # Authentication screens
│   │   ├── smart/             # Smart wallet screens
│   │   └── wallet/            # Wallet management screens
│   └── utils/                 # Utility functions
├── android/                   # Android native code
├── ios/                       # iOS native code
├── __tests__/                 # Test files
└── ...config files
```

## 🎨 Component Library

The app includes a comprehensive custom component library:

- **web23-button**: Customizable button component
- **web23-input**: Styled input fields
- **web23-modal**: Modal dialogs
- **web23-checkbox**: Custom checkboxes
- **web23-toggle**: Toggle switches
- **web23-avatar**: User avatars
- **web23-searchbox**: Search functionality
- **web23-spinner**: Loading indicators
- **web23-popup**: Popup notifications
- **mnemonic-box**: Secure phrase display
- And many more...

## 🔧 Configuration

### TypeScript Path Aliases

The project uses path aliases for cleaner imports:

```typescript
@api/*        → src/api/*
@assets/*     → src/assets/*
@components/* → src/components/*
@navigation/* → src/navigation/*
@screens/*    → src/screens/*
@utils/*      → src/utils/*
@layouts/*    → src/layouts/*
```

### Environment Variables

Create a `.env` file in the root directory (refer to `.env.example` if available) for environment-specific configurations.

## 📱 Platform Support

- **Android**: API Level 21+
- **iOS**: iOS 12.0+

## 🔐 Security Features

- Secure storage for private keys and mnemonics
- Password encryption
- Biometric authentication support (planned)
- Secure communication with Hedera network

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

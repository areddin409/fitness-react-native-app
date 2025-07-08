# 💪 FitApp - Smart Fitness Tracking

A comprehensive mobile fitness application built with React Native and Expo, featuring AI-powered workout guidance, real-time tracking, and intelligent progress analytics.

## ✨ Features

### 📱 Mobile Development with React Native & Expo
- **Cross-platform compatibility** - Single codebase for iOS and Android
- **Real-time workout tracking** with live timers and stopwatch functionality
- **Touch-optimized interface** designed specifically for mobile devices
- **TypeScript integration** for type safety and enhanced development experience
- **State management with Zustand** for efficient and scalable data handling

### 🗂️ Content Management with Sanity CMS
- **Flexible exercise database** with rich images and detailed descriptions
- **Rich content editor** for creating comprehensive exercise instructions
- **Media uploads and optimization** for demonstration videos and images
- **Custom schemas** specifically designed for fitness content
- **Headless CMS architecture** for flexible content management and delivery

### 💪 Fitness Tracking Features
- **Smart workout tracking** with detailed set and rep logging
- **Built-in stopwatch** for accurate workout duration tracking
- **Progress analytics** to monitor your fitness journey with comprehensive statistics
- **Comprehensive exercise library** with step-by-step instructions
- **Unit flexibility** - easily switch between kg and lbs for weight tracking
- **Workout history** to track progress over time

### 🤖 AI Integration & Guidance
- **Personalized exercise instructions** powered by OpenAI
- **AI-powered exercise guidance** and real-time tips
- **Intelligent workout recommendations** based on your fitness level
- **Real-time AI assistance** during workouts for proper form and technique

### � Authentication & User Management
- **Secure authentication** with Clerk integration
- **Google OAuth** for seamless sign-in experience
- **Protected user data** and comprehensive workout history
- **User profile management** with personalized settings

### 🎨 Modern UI/UX Design
- **Beautiful interface** styled with NativeWind/Tailwind CSS
- **Intuitive tab-based navigation** with smooth workout flow
- **Consistent design system** with unified color scheme and typography
- **Smooth animations** with fluid transitions and micro-interactions
- **Loading states** with clear feedback during data operations
- **Accessibility support** with screen reader compatibility

### 🌟 Professional Mobile Features
- **Responsive design** optimized for all screen sizes
- **Mobile-first approach** ensuring optimal mobile experience
- **Cross-platform compatibility** with native performance
- **Real-time progress tracking** and comprehensive analytics

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or later)
- npm or yarn
- Expo CLI
- iOS Simulator (for iOS development) or Android Studio (for Android development)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/fitness-react-native-app.git
   cd fitness-react-native-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env.local` file in the root directory and add your configuration:
   ```env
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
   EXPO_PUBLIC_SANITY_PROJECT_ID=your_sanity_project_id
   EXPO_PUBLIC_SANITY_DATASET=your_sanity_dataset
   EXPO_PUBLIC_OPENAI_API_KEY=your_openai_api_key
   ```

4. **Start the development server**
   ```bash
   npm start
   ```

### Running on Different Platforms

- **iOS Simulator**: `npm run ios`
- **Android Emulator**: `npm run android`
- **Web Browser**: `npm run web`

## 📱 Tech Stack

- **Frontend**: React Native, Expo Router, TypeScript
- **Styling**: NativeWind (Tailwind CSS for React Native)
- **State Management**: Zustand
- **Authentication**: Clerk
- **Backend/CMS**: Sanity CMS
- **AI Integration**: OpenAI API
- **Development**: Expo SDK 53, Metro bundler

## 📖 Project Structure

```
src/
├── app/                    # Expo Router pages
│   ├── _layout.tsx        # Root layout
│   ├── index.tsx          # Home screen
│   ├── history.tsx        # Workout history
│   └── profile/           # Profile screens
├── components/            # Reusable components
├── hooks/                 # Custom React hooks
├── lib/                   # Utility functions and configurations
├── stores/                # Zustand stores
├── types/                 # TypeScript type definitions
└── global.css            # Global styles
```

## 🔧 Configuration

### Tailwind CSS
The app uses NativeWind for styling, which brings Tailwind CSS to React Native. Configuration is in `tailwind.config.js`.

### Expo Router
Navigation is handled by Expo Router with file-based routing. The app structure follows the `src/app/` directory convention.

## 🚀 Deployment

### Web Deployment
```bash
npm run deploy
```

### Mobile App Deployment
1. **Build for production**
   ```bash
   npx eas build --platform all
   ```

2. **Submit to app stores**
   ```bash
   npx eas submit --platform all
   ```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Expo Team** for the amazing React Native framework
- **Tailwind CSS** for the utility-first CSS framework
- **Sanity** for the flexible headless CMS
- **Clerk** for seamless authentication
- **OpenAI** for AI-powered features

## 📞 Support

If you have any questions or need help, please open an issue or contact us at [your-email@example.com](mailto:your-email@example.com).

---

Made with ❤️ and 💪 for the fitness community

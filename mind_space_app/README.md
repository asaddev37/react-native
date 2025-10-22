# Mind Space - Mental Wellness App

A comprehensive React Native Expo app for mental wellness tracking, AI-powered support, and wellness resources.

## Features

### 🔐 Authentication
- Firebase Authentication with email/password
- User profile management
- Secure session handling

### 📝 Journaling System
- Rich text journal entries
- Mood tagging and categorization
- Entry search and organization
- Privacy controls

### 🤖 AI-Powered Chat
- Gemini AI integration for mental health support
- Context-aware conversations
- Personalized wellness guidance
- Crisis support resources

### 📊 Mood Tracking
- Visual mood tracking (1-10 scale)
- Mood history and trends
- Factor analysis (sleep, exercise, work, etc.)
- Statistical mood insights

### 📚 Wellness Resources
- Educational content
- Coping strategies
- Meditation exercises
- Emergency support contacts

### 📱 Dashboard & Analytics
- Personal dashboard with insights
- Mood statistics and trends
- Recent activity overview
- Quick action buttons

## Tech Stack

- **Frontend**: React Native with Expo
- **Backend**: Firebase (Firestore, Auth, Storage)
- **AI**: Google Gemini API
- **Navigation**: Expo Router
- **Styling**: React Native StyleSheet
- **State Management**: React Hooks

## Project Structure

```
mind-space-app/
├── app/                          # Expo Router app directory
│   ├── (auth)/                   # Authentication screens
│   │   ├── login.tsx
│   │   ├── register.tsx
│   │   └── _layout.tsx
│   ├── (tabs)/                   # Main app tabs
│   │   ├── index.tsx            # Dashboard
│   │   ├── journal.tsx          # Journal entries
│   │   ├── chat.tsx             # AI Chat
│   │   ├── mood.tsx             # Mood tracking
│   │   ├── resources.tsx       # Wellness resources
│   │   └── _layout.tsx
│   └── _layout.tsx              # Root layout
├── components/                   # Reusable components
├── services/                     # Firebase services
│   ├── auth.ts
│   ├── firestore.ts
│   └── ai.ts
├── config/                       # Configuration files
│   ├── firebase.ts
│   └── gemini.ts
├── types/                        # TypeScript types
├── utils/                        # Utility functions
├── constants/                    # App constants
└── assets/                       # Images, fonts, etc.
```

## Setup Instructions

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- Expo CLI
- Android Studio (for Android development)
- Xcode (for iOS development, macOS only)

### Installation

1. **Clone and navigate to the project:**
   ```bash
   cd mind-space-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Firebase Configuration:**
   - The Firebase configuration is already set up with your credentials
   - `google-services.json` is configured for Android
   - Firebase project: `mind-space-254a5`

4. **Gemini AI Configuration:**
   - Gemini API key is configured in `config/gemini.ts`
   - Model: `gemini-1.5-pro`

### Running the App

1. **Start the development server:**
   ```bash
   npm start
   ```

2. **Run on specific platforms:**
   ```bash
   # Android
   npm run android
   
   # iOS (macOS only)
   npm run ios
   
   # Web
   npm run web
   ```

3. **Using Expo Go app:**
   - Install Expo Go on your mobile device
   - Scan the QR code from the terminal
   - The app will load on your device

## Firebase Collections

### Users
- User profile information
- Authentication data
- Preferences and settings

### Journals
- Journal entries with content
- Mood tags and metadata
- User associations

### Moods
- Mood entries with ratings
- Factor analysis
- Timestamps

### Chat History
- AI conversation history
- User messages and AI responses
- Context data

### Insights
- AI-generated insights
- Mood pattern analysis
- Personalized recommendations

### Resources
- Wellness resources
- Articles and tips
- Admin-managed content

## Key Features Implementation

### Authentication Flow
- Login/Register screens with Firebase Auth
- Automatic navigation based on auth state
- User profile management

### AI Integration
- Gemini AI for mental health support
- Context-aware responses
- Crisis support detection
- Personalized insights

### Real-time Data
- Firestore listeners for live updates
- Offline support with Firebase
- Optimistic UI updates

### Mobile-First Design
- Responsive layouts
- Touch-friendly interactions
- Native performance
- Offline capabilities

## Development Notes

### Environment Variables
- Firebase configuration is hardcoded for development
- Gemini API key is included in the config
- For production, move sensitive data to environment variables

### Security
- Firebase Security Rules should be configured
- API keys should be secured in production
- User data is encrypted in transit

### Performance
- Lazy loading for better performance
- Image optimization
- Efficient Firestore queries
- Caching strategies

## Next Steps

1. **Testing**: Add unit and integration tests
2. **Push Notifications**: Implement Firebase Cloud Messaging
3. **Offline Support**: Enhanced offline capabilities
4. **Analytics**: User behavior tracking
5. **Admin Panel**: Content management system
6. **Therapist Integration**: Professional support features

---
made by ....................
in this work
we have some innocent persons

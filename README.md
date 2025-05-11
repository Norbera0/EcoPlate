# 🌱 **GreenBite: Carbon Footprint Food Tracker App**

GreenBite is a modern web application that helps users understand and reduce their environmental impact through meal tracking and AI-powered carbon footprint analysis. Built with Next.js and powered by AI, it provides real-time insights into the environmental impact of your food choices.

## 🚀 **Core Features**

### 1. 📷 **AI-Powered Meal Logging**
- Take photos of your meals
- AI automatically identifies food items and estimates quantities
- Edit and confirm food items before saving
- Instant carbon footprint calculation
- Smart feedback and suggestions

### 2. 📊 **Progress Tracking & Analytics**
- Daily and weekly carbon footprint reports
- Interactive charts and visualizations
- Comparison with national averages
- Detailed meal history and insights
- Achievement tracking and streaks

### 3. 💡 **AI-Powered Recommendations**
- Personalized eco-friendly food suggestions
- Smart meal alternatives
- AI chatbot for sustainability advice
- Custom tips based on eating patterns

### 4. 🏆 **Gamification & Engagement**
- Daily and weekly challenges
- Achievement badges
- Streak tracking
- Progress milestones

## 🛠️ **Technical Stack**

- **Frontend Framework**: Next.js 15 with React 18
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **State Management**: React Context API
- **AI Integration**: Google AI (via GenKit)
- **Authentication**: Firebase
- **Data Visualization**: Recharts
- **Form Handling**: React Hook Form with Zod validation

## 📱 **App Structure**

### Pages
- `/` - Home/Dashboard
- `/log-meal` - Meal logging interface
- `/meal-result` - Meal analysis results
- `/reports` - Progress and analytics
- `/review-meal` - Meal review and feedback
- `/login` - Authentication

### Key Components
- AI-powered food recognition
- Carbon footprint calculator
- Progress charts and analytics
- Recommendation engine
- User authentication
- Data persistence

## 🚀 **Getting Started**

### Prerequisites
- Node.js (Latest LTS version)
- npm or yarn
- Firebase account
- Google AI API key

### Installation

1. Clone the repository:
```bash
git clone https://github.com/Norbera0/EcoPlate.git
cd EcoPlate
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Set up environment variables:
Create a `.env.local` file with:
```
NEXT_PUBLIC_FIREBASE_API_KEY=your_firebase_api_key
NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN=your_firebase_auth_domain
NEXT_PUBLIC_FIREBASE_PROJECT_ID=your_firebase_project_id
NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET=your_firebase_storage_bucket
NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID=your_firebase_messaging_sender_id
NEXT_PUBLIC_FIREBASE_APP_ID=your_firebase_app_id
GOOGLE_AI_API_KEY=your_google_ai_api_key
```

4. Start the development server:
```bash
npm run dev
# or
yarn dev
```

The application will be available at `http://localhost:9002`

## 📁 **Project Structure**

```
src/
├── ai/              # AI integration and carbon footprint estimation
├── app/             # Next.js app router pages
├── components/      # Reusable UI components
├── context/         # React context providers
├── hooks/           # Custom React hooks
├── lib/             # Utility functions and configurations
└── services/        # API and external service integrations
```

## 🤝 **Contributing**

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 **License**

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 **Acknowledgments**

- Next.js
- Tailwind CSS
- Radix UI
- Google AI
- Firebase
- Recharts

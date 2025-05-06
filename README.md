# EcoPlate 🌱

EcoPlate is a modern web application that helps users track and reduce their carbon footprint through meal logging and analysis. Built with Next.js and powered by AI, it provides insights into the environmental impact of your food choices.

## Features

- 📸 **Meal Logging**: Log your meals by taking photos and inputting quantities
- 🌍 **Carbon Footprint Estimation**: AI-powered estimation of meal carbon footprints
- 📊 **Progress Tracking**: Monitor your environmental impact with daily and weekly reports
- 📈 **Visual Analytics**: Interactive charts and graphs showing your carbon footprint trends
- 🔐 **User Authentication**: Secure login and personal data management

## Tech Stack

- **Frontend**: Next.js 15, React 18, TypeScript
- **Styling**: Tailwind CSS, Radix UI Components
- **State Management**: React Context API
- **AI Integration**: Google AI (via GenKit)
- **Authentication**: Firebase
- **Data Visualization**: Recharts
- **Form Handling**: React Hook Form with Zod validation

## Getting Started

### Prerequisites

- Node.js (Latest LTS version recommended)
- npm or yarn
- Firebase account (for authentication)
- Google AI API key (for carbon footprint estimation)

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

3. Create a `.env.local` file in the root directory with your environment variables:
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

## Project Structure

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

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Next.js](https://nextjs.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Google AI](https://ai.google.dev/)
- [Firebase](https://firebase.google.com/)

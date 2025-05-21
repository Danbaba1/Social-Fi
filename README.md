# SocialFi Rewards Platform

A React-based web application that lets users earn rewards by completing social media tasks. This platform connects brands with users willing to engage with their content on social platforms, primarily Twitter.



## 🚀 Features

- **Task Marketplace**: Browse and complete social media tasks from various brands
- **Reward System**: Earn USD rewards for completing tasks
- **Mobile Money Integration**: Withdraw earnings directly to mobile money accounts
- **User-friendly Onboarding**: Simple 4-step onboarding process
- **Dashboard**: Track available tasks and earnings in real-time

## 📋 Project Structure

```
src/
├── components/
│   ├── Dashboard.tsx            # Main dashboard component
│   ├── Header.tsx               # App header with navigation and balance
│   ├── TaskCard.tsx             # Individual task display component
│   ├── TaskDetailModal.tsx      # Modal for task details and starting tasks
│   ├── TaskCompletionModal.tsx  # Modal for submitting completed tasks
│   ├── WithdrawalModal.tsx      # Modal for withdrawing funds
│   └── onboarding/              # Onboarding flow components
│       ├── OnboardingFlow.tsx   # Main onboarding container
│       └── steps/               # Individual onboarding steps
│           ├── WelcomeStep.tsx
│           ├── ProfileStep.tsx
│           ├── SocialAccountsStep.tsx
│           └── PaymentSetupStep.tsx
├── store/
│   └── useStore.ts              # State management with hooks
├── types.ts                     # TypeScript type definitions
└── App.tsx                      # Main application component
```

## 🔧 Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/socialfi-rewards.git
cd socialfi-rewards
```

2. Install dependencies
```bash
npm install
# or
yarn install
```

3. Start the development server
```bash
npm start
# or
yarn start
```

The application will be available at `http://localhost:3000`

## 💻 Technology Stack

- **React**: UI library
- **TypeScript**: For type safety
- **Tailwind CSS**: For styling
- **Lucide Icons**: For UI icons
- **React Hot Toast**: For notifications

## 🌍 User Journey

1. **Onboarding**:
   - Welcome introduction
   - Profile creation
   - Social account connection
   - Payment method setup

2. **Task Completion**:
   - Browse available tasks on the dashboard
   - View task details
   - Complete tasks on Twitter
   - Submit proof of completion (tweet link)

3. **Rewards**:
   - Accumulate rewards for verified tasks
   - Withdraw earnings to mobile money account

## 🔒 Authentication & Security

- Simple email-based authentication
- Secure withdrawal process
- Verification of task completion before reward distribution

## 💰 Payment Methods

Currently supported payment methods:
- MTN Mobile Money
- Flutterwave (for bank transfers)

## 🛠️ Development

### Prerequisites

- Node.js (v14+)
- npm or yarn

### Environment Variables

Create a `.env` file in the root directory:

```
REACT_APP_API_URL=your_api_url_here
```

### Building for Production

```bash
npm run build
# or
yarn build
```

## 📱 Future Enhancements

- Support for additional social media platforms (Instagram, TikTok)
- Referral program
- In-app notifications
- Task categories and filtering
- Analytics dashboard for brands

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👥 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For support, email support@socialfirewards.com or join our Discord community.

---

Built with ❤️ for connecting brands and social media users in a rewarding way.

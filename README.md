# AfricaCrypto - Cryptocurrency Education Platform

A comprehensive cryptocurrency education platform specifically designed for African communities, built with React, TypeScript, and modern web technologies.

## 🌍 About AfricaCrypto

AfricaCrypto is an educational platform that empowers African communities with comprehensive cryptocurrency knowledge. The platform offers structured learning modules covering everything from basic blockchain concepts to advanced trading principles and wallet security.

## ✨ Features

- **7 Comprehensive Learning Modules**
  - Module 1: Introduction to Digital Currency
  - Module 2: Understanding Blockchain Technology
  - Module 3: Blockchain Deep Dive
  - Module 4: Popular Cryptocurrencies
  - Module 5: Cryptocurrency Exchanges & Economic Impact
  - Module 6: Crypto Communities & Wallets
  - Module 7: Setting Up Digital Wallets

- **Interactive Learning Experience**
  - Progress tracking system
  - Module-based quizzes
  - Sequential learning path
  - Responsive design for all devices

- **Modern UI/UX**
  - Dark/Light theme support
  - African-inspired design elements
  - Accessibility features
  - Mobile-first responsive design

- **User Authentication**
  - Secure user registration and login
  - Progress persistence
  - User profiles and dashboards

## 🛠️ Technology Stack

- **Frontend Framework**: React 18 with TypeScript
- **Build Tool**: Vite
- **Styling**: Tailwind CSS with custom design system
- **UI Components**: Radix UI primitives with shadcn/ui
- **Authentication**: Supabase Auth
- **Database**: Supabase PostgreSQL
- **State Management**: React Query (TanStack Query)
- **Routing**: React Router v6
- **Icons**: Lucide React
- **Fonts**: Ubuntu & Inter (Google Fonts)

## 📁 Project Structure

```
src/
├── components/           # Reusable UI components
│   ├── ui/              # shadcn/ui components
│   ├── Module1/         # Module 1 specific components
│   ├── Module2/         # Module 2 specific components
│   ├── Module3/         # Module 3 specific components
│   ├── Module4/         # Module 4 specific components
│   ├── Module5/         # Module 5 specific components
│   ├── Module6/         # Module 6 specific components
│   ├── Module7/         # Module 7 specific components
│   └── ...
├── contexts/            # React contexts
├── hooks/               # Custom React hooks
├── integrations/        # Third-party integrations
├── lib/                 # Utility libraries
├── pages/               # Page components
└── assets/              # Static assets
```

## 🚀 Getting Started

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn
- Git

### Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/africacrypto.git
cd africacrypto
```

2. Install dependencies:
```bash
npm install
```

3. Set up environment variables:
```bash
cp .env.example .env.local
```

4. Configure your Supabase credentials in `.env.local`:
```
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

5. Start the development server:
```bash
npm run dev
```

The application will be available at `http://localhost:8080`

## 📚 Learning Modules Overview

### Module 1: Introduction to Digital Currency
Basic concepts of digital currency, its evolution, and fundamental principles.

### Module 2: Understanding Blockchain Technology
Core blockchain technology concepts, consensus mechanisms, and network types.

### Module 3: Blockchain Deep Dive
Advanced blockchain concepts including applications, features, types, and history.

### Module 4: Popular Cryptocurrencies
Overview of major cryptocurrencies, price factors, and research methodologies.

### Module 5: Cryptocurrency Exchanges & Economic Impact
Understanding exchanges, trading platforms, and economic implications.

### Module 6: Crypto Communities & Wallets
Community aspects of cryptocurrency and basic wallet concepts.

### Module 7: Setting Up Digital Wallets
Comprehensive guide to wallet types, setup procedures, and security practices.

## 🔐 Authentication & Database

The platform uses Supabase for:
- User authentication (email/password)
- Progress tracking
- User profiles
- Quiz results storage

## 🎨 Design System

The platform features a custom design system built with:
- Semantic color tokens
- Responsive typography scale
- Consistent spacing system
- Dark/light theme support
- African-inspired color palette

## 📱 Responsive Design

The platform is fully responsive and optimized for:
- Mobile devices (320px+)
- Tablets (768px+)
- Desktop (1024px+)
- Large screens (1440px+)

## 🧪 Testing

```bash
# Run tests
npm run test

# Run tests with coverage
npm run test:coverage
```

## 🔧 Build & Deployment

```bash
# Build for production
npm run build

# Preview production build
npm run preview
```

## 📦 Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint
- `npm run type-check` - Run TypeScript type checking

## 🌍 Deployment

The application can be deployed on various platforms:

### Vercel (Recommended)
1. Connect your GitHub repository to Vercel
2. Add environment variables in Vercel dashboard
3. Deploy automatically on push to main branch

### Netlify
1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `dist`
4. Add environment variables

### Other Platforms
The built application in the `dist` folder can be deployed to any static hosting service.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🎯 Roadmap

- [ ] Additional trading modules
- [ ] Advanced DeFi education
- [ ] Interactive simulations
- [ ] Community features
- [ ] Multi-language support
- [ ] Mobile app development

## 🐛 Issues & Support

If you encounter any issues or have questions:
1. Check existing [Issues](https://github.com/yourusername/africacrypto/issues)
2. Create a new issue with detailed description
3. Include steps to reproduce the problem

## 📞 Contact

- Project Maintainer: [Your Name]
- Email: [your.email@example.com]
- Twitter: [@yourhandle]

## 🙏 Acknowledgments

- African cryptocurrency communities for inspiration
- Open source contributors
- Educational content reviewers
- UI/UX design community

---

**Built with ❤️ for African cryptocurrency education**

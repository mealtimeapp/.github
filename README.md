# 🍽️ Mealtime

> **Modern group food ordering made effortless**

Welcome to Mealtime – the platform that revolutionizes how groups order food together. Whether it's a team lunch, family dinner, or friends gathering, Mealtime makes coordinating group orders simple, fair, and fun.

---

## 🌟 About Mealtime

Mealtime solves a problem we've all experienced: organizing food orders for groups is chaotic. Phone calls, menu screenshots, payment confusion, and the inevitable "who ordered what?" debates.

We built Mealtime to eliminate this friction. Our platform enables seamless group ordering with transparent pricing, flexible payment options, and a delightful user experience across all devices.

### 🎯 The Problem We Solve

- **Coordination Chaos**: No more passing around phones or forwarding menu screenshots
- **Payment Headaches**: Split bills fairly and automatically
- **Time Waste**: Reduce ordering time from 30+ minutes to under 5 minutes
- **Order Errors**: Clear item assignments mean everyone gets exactly what they ordered

### ✨ Our Solution

A unified platform where one person starts an order, shares a link, and everyone adds their items. When the order closes, each person pays their share directly through the app. Simple, transparent, efficient.

---

## 🚀 Key Features

### For Customers

- **📱 Multi-Platform Access**
  - Native mobile apps (iOS & Android)
  - Responsive web application
  - Seamless experience across all devices

- **👥 Group Ordering**
  - Create or join group orders with a simple link
  - Real-time order updates
  - See who ordered what
  - Automatic price splitting

- **💳 Flexible Payments**
  - Individual payment per person
  - Integrated with Mollie payment gateway
  - Secure and instant transactions
  - Support for all major payment methods

- **🎟️ User Balance System**
  - Load credits to your account
  - Pay from balance for faster checkout
  - Track transaction history
  - Perfect for regular group members

- **🔔 Smart Notifications**
  - Order status updates
  - Payment reminders
  - Delivery tracking
  - Group activity alerts

### For Restaurants

- **📊 Comprehensive Dashboard**
  - Real-time order management
  - Menu and pricing control
  - Analytics and insights
  - Financial reporting

- **🍕 Menu Management**
  - Easy menu creation and updates
  - Category organization
  - Photo uploads with automatic optimization
  - Flexible pricing (dine-in vs. takeaway)
  - Option groups (toppings, sizes, etc.)

- **⏰ Smart Scheduling**
  - Opening hours configuration
  - Order deadlines
  - Delivery area management
  - Preparation time settings

- **💰 Financial Tools**
  - Automated invoicing
  - Revenue tracking
  - Commission management
  - Payment reconciliation

### For Administrators

- **🎛️ Platform Control**
  - User management
  - Restaurant onboarding
  - System settings
  - Content moderation

- **📈 Advanced Analytics**
  - Platform-wide metrics
  - Revenue insights
  - User behavior analysis
  - Restaurant performance tracking

- **🔐 Security & Compliance**
  - Role-based access control
  - Audit logging
  - Data privacy controls
  - Payment integrity monitoring

---

## 🏗️ Technology Stack

### Modern, Scalable Architecture

```
┌─────────────────────────────────────────────────────────┐
│                    Client Applications                   │
├─────────────────────────────────────────────────────────┤
│  📱 Mobile (React Native + Expo)                        │
│  🌐 Web (Next.js 15 + React 19)                         │
│  🏢 Restaurant Portal (Next.js)                         │
│  ⚙️  Admin Dashboard (Next.js)                          │
└─────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────┐
│              🚀 Backend API (NestJS)                     │
│              GraphQL + REST endpoints                    │
└─────────────────────────────────────────────────────────┘
                            ↕
┌─────────────────────────────────────────────────────────┐
│              💾 Database & Storage                       │
│  PostgreSQL + Prisma ORM                                │
│  S3-compatible storage (DigitalOcean Spaces)            │
│  Redis (caching & sessions)                             │
└─────────────────────────────────────────────────────────┘
```

### Core Technologies

#### Frontend
- **React 19** - Latest React with enhanced performance
- **Next.js 15** - Server-side rendering and static generation
- **React Native 0.82** - Native mobile experience
- **Expo 54** - Simplified React Native development
- **TailwindCSS + NativeWind** - Unified styling system
- **TypeScript** - Type-safe codebase

#### Backend
- **NestJS** - Enterprise-grade Node.js framework
- **GraphQL** - Efficient data fetching with Apollo Server
- **Prisma** - Type-safe database ORM
- **PostgreSQL** - Robust relational database
- **JWT** - Secure authentication

#### Infrastructure
- **Turborepo** - Monorepo management
- **Docker** - Containerized deployments
- **GitHub Actions** - CI/CD automation
- **DigitalOcean** - Cloud hosting
- **imgproxy** - On-the-fly image optimization

#### Services & Integrations
- **Mollie** - Payment processing
- **Twilio** - SMS notifications
- **Brevo** - Email services
- **PostHog** - Product analytics
- **Mapbox** - Address geocoding

---

## 📦 Project Structure

```
mealtime/
├── apps/
│   ├── mobile/              # React Native mobile app
│   ├── web/                 # Customer web application
│   ├── restaurant-web/      # Restaurant dashboard
│   ├── admin-web/           # Admin control panel
│   └── backend/             # NestJS GraphQL API
│
├── packages/
│   ├── types/               # Shared TypeScript types
│   ├── ui/                  # Reusable UI components
│   └── assets/              # Shared images, fonts, icons
│
├── .github/workflows/       # CI/CD pipelines
├── docs/                    # Documentation
└── scripts/                 # Automation scripts
```

---

## 🔄 Development Workflow

### Monorepo Benefits
- **Shared Code**: Reuse types, utilities, and components across apps
- **Atomic Changes**: Update multiple apps in a single PR
- **Consistent Tooling**: Unified linting, testing, and building
- **Fast Builds**: Turborepo's intelligent caching

### CI/CD Pipeline
- **Automated Testing**: Type checking, linting, and unit tests
- **Multi-Environment**: Development, staging, and production
- **Mobile Builds**: GitHub Actions for iOS and Android
- **Docker Deployments**: Automated container builds and deployments
- **Zero-Downtime**: Rolling updates with health checks

---

## 🎨 Design Philosophy

### User-Centric Design
- **Intuitive**: No learning curve – anyone can use it
- **Fast**: Optimized for speed at every step
- **Accessible**: WCAG compliant, keyboard navigation, screen reader support
- **Responsive**: Beautiful on phones, tablets, and desktops

### Technical Excellence
- **Type Safety**: TypeScript everywhere reduces bugs
- **Performance**: Lazy loading, code splitting, image optimization
- **Scalability**: Designed to handle thousands of concurrent orders
- **Maintainability**: Clean code, comprehensive documentation

### Security First
- **Encrypted Communications**: HTTPS/TLS everywhere
- **Secure Authentication**: JWT with refresh tokens, 2FA support
- **Payment Security**: PCI-compliant through Mollie
- **Data Privacy**: GDPR compliant, user data protection
- **Input Validation**: Server-side validation for all inputs

---

## 📊 By the Numbers

### Platform Metrics *(as of November 2025)*
- 🏪 **Restaurants**: Growing network of partner restaurants
- 👥 **Users**: Active community of group order organizers
- 📱 **Mobile Apps**: Available on iOS and Android
- 🌐 **Web Platform**: Fully responsive web application
- ⚡ **API**: High-performance GraphQL endpoint

### Technical Stats
- 📁 **Codebase**: ~124,000 lines of code
- 📦 **Packages**: 6 workspaces in monorepo
- 🧪 **Type Safety**: 100% TypeScript coverage
- 🎨 **Components**: Shared component library
- 📚 **Documentation**: Comprehensive guides and API docs

---

## 🛠️ Development Setup

### Prerequisites
- Node.js 20+
- npm or yarn
- PostgreSQL 14+
- Docker (optional, for local services)

### Quick Start

```bash
# Clone the repository
git clone https://github.com/mealtimeapp/mealtime.git
cd mealtime

# Install dependencies
npm install

# Set up environment variables
cp apps/backend/.env.example apps/backend/.env.development

# Run database migrations
cd apps/backend
npx prisma migrate dev

# Start development servers
npm run dev
```

### Available Commands

```bash
npm run dev           # Start all apps in development mode
npm run build         # Build all apps for production
npm run lint          # Lint all packages
npm run typecheck     # Type check all packages
npm run test          # Run all tests
```

---

## 🤝 Contributing

We welcome contributions from the community! Whether it's:

- 🐛 **Bug Reports**: Found an issue? Let us know!
- 💡 **Feature Requests**: Have an idea? We'd love to hear it!
- 🔧 **Pull Requests**: Want to contribute code? Amazing!
- 📖 **Documentation**: Help improve our docs
- 🌍 **Translations**: Make Mealtime multilingual

### Development Guidelines
- Follow our code style (enforced by ESLint)
- Write tests for new features
- Update documentation as needed
- Keep commits atomic and descriptive
- Ensure all CI checks pass

---

## 🗺️ Roadmap

### Current Focus (Q4 2025)
- ✅ Core platform MVP
- ✅ Mobile apps (iOS & Android)
- ✅ Restaurant onboarding
- 🚧 Enhanced analytics dashboard
- 🚧 Marketing campaigns feature
- 🚧 Advanced group features

### Upcoming Features
- 🔮 **AI-Powered Recommendations**: Smart menu suggestions
- 🔮 **Loyalty Programs**: Reward frequent users
- 🔮 **Scheduled Orders**: Plan ahead for future dates
- 🔮 **Diet Preferences**: Filter by allergies and dietary needs
- 🔮 **Social Features**: Follow friends, share favorite restaurants
- 🔮 **Multi-Language**: Dutch, English, and more
- 🔮 **Integration APIs**: Connect with third-party platforms

---

## 📱 Platform Availability

### Mobile Apps
- 📲 **iOS**: Available on App Store *(coming soon)*
- 🤖 **Android**: Available on Google Play *(coming soon)*

### Web Applications
- 🌐 **Customer App**: [mealtime.nl](https://mealtime.nl)
- 🏢 **Restaurant Portal**: [restaurant.mealtime.nl](https://restaurant.mealtime.nl)
- ⚙️ **Admin Dashboard**: [admin.mealtime.nl](https://admin.mealtime.nl)

---

## 📞 Contact & Support

### For Customers
- 🌐 Visit: [mealtime.nl](https://mealtime.nl)
- 📧 Email: support@mealtime.nl
- 💬 In-app support chat

### For Restaurants
- 🏢 Partner Portal: [restaurant.mealtime.nl](https://restaurant.mealtime.nl)
- 📧 Email: restaurants@mealtime.nl
- 📞 Phone: Available in restaurant dashboard

### For Developers
- 💻 GitHub: [@mealtimeapp](https://github.com/mealtimeapp)
- 📚 Documentation: Coming soon
- 🐛 Issue Tracker: [GitHub Issues](https://github.com/mealtimeapp/mealtime/issues)

---

## 📄 License & Legal

### Privacy First
We take your privacy seriously. Our platform is built with privacy by design:
- Minimal data collection
- GDPR compliant
- Transparent privacy policy
- User data control and deletion rights

### Terms & Policies
- 📜 [Terms of Service](https://mealtime.nl/algemene-voorwaarden)
- 🔒 [Privacy Policy](https://mealtime.nl/privacy-policy)
- 🍪 [Cookie Policy](https://mealtime.nl/privacy-policy)

---

## 🙏 Acknowledgments

Built with ❤️ using amazing open-source technologies:
- React, Next.js, and the JavaScript ecosystem
- NestJS and the Node.js community
- Prisma for type-safe database access
- All our open-source dependencies

Special thanks to:
- Our early adopters and beta testers
- Restaurant partners who believed in our vision
- The developer community for incredible tools and libraries

---

## 🌟 Why Mealtime?

In a world where food brings people together, ordering shouldn't be a hassle. Mealtime eliminates the friction in group food ordering, making it as simple as sharing a link.

We're not just building software – we're creating moments of joy when friends, families, and colleagues share meals together without the stress of coordination.

**Join us in revolutionizing group food ordering. Together, let's make every meal time a great time.** 🍕🍔🍜

---

<div align="center">

**[Visit Mealtime](https://mealtime.nl)** • **[GitHub](https://github.com/mealtimeapp)** • **[Contact Us](mailto:hello@mealtime.nl)**

Made with 💙 in the Netherlands

</div>

<div align="center">
  <h1>🛒 ShopQuick</h1>
  <p><em>A modern, full-stack multi-vendor e-commerce platform</em></p>
  
  <p>
    <a href="https://gocartshop.in" target="_blank">
      <img src="https://img.shields.io/badge/🌐_Live_Demo-Visit_Site-blue?style=for-the-badge" alt="Live Demo">
    </a>
    <a href="https://github.com/ayushpremrocks/shopquick/blob/main/LICENSE.md">
      <img src="https://img.shields.io/github/license/ayushpremrocks/shopquick?style=for-the-badge" alt="License">
    </a>
    <a href="https://github.com/ayushpremrocks/shopquick/pulls">
      <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=for-the-badge" alt="PRs Welcome">
    </a>
    <a href="https://github.com/ayushpremrocks/shopquick/issues">
      <img src="https://img.shields.io/github/issues/ayushpremrocks/shopquick?style=for-the-badge" alt="GitHub issues">
    </a>
  </p>
  
  <p>
    Built with Next.js, PostgreSQL, and modern web technologies for seamless multi-vendor commerce experience.
  </p>
</div>

---

## 🌟 Overview

ShopQuick is a comprehensive multi-vendor e-commerce platform that enables entrepreneurs to create their own online stores and sell products through a unified marketplace. With features like admin approval workflows, premium subscriptions, and integrated payment processing, it provides everything needed to run a modern e-commerce business.

**🔗 Live Demo:** [ShopQuick](https://shop-quick-gndt.vercel.app)

---

## ✨ Key Features

### 🏪 **Multi-Vendor Marketplace**
- **Store Creation**: Users can easily create and customize their own online stores
- **Admin Approval**: Secure store approval process to maintain platform quality
- **Vendor Management**: Comprehensive tools for vendor onboarding and management

### 👥 **User Experience**
- **Customer Storefront**: Beautiful, responsive interface for browsing and purchasing
- **Vendor Dashboards**: Dedicated analytics and product management tools
- **Admin Panel**: Complete oversight of stores, products, and commissions

### 💳 **E-commerce Essentials**
- **Stripe Integration**: Secure payment processing for all transactions
- **Premium Subscriptions**: Subscription billing for enhanced store features
- **Discount System**: Flexible coupon and discount management
- **Order Management**: Complete order tracking and fulfillment system

### 🔐 **Security & Authentication**
- **Clerk Auth**: Seamless user authentication and management
- **Role-based Access**: Different permission levels for customers, vendors, and admins
- **Secure Transactions**: Industry-standard security practices

---

## 🛠️ Tech Stack

| Category | Technology | Purpose |
|----------|------------|---------|
| **Frontend** | Next.js 14 | React framework with App Router |
| **Styling** | Tailwind CSS | Utility-first CSS framework |
| **Database** | Neon PostgreSQL | Serverless PostgreSQL database |
| **Authentication** | Clerk | User management and authentication |
| **Image Storage** | ImageKit | Cloud-based image optimization |
| **Background Jobs** | Inngest | Job scheduling and management |
| **Payments** | Stripe | Payment processing |
| **State Management** | Redux Toolkit | Predictable state container |
| **Icons** | Lucide React | Beautiful icon library |
| **Deployment** | Vercel | Serverless deployment platform |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18.x or later
- npm, yarn, pnpm, or bun
- PostgreSQL database (via Neon)
- Clerk account for authentication
- ImageKit account for image storage
- Stripe account for payments

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/ayushpremrocks/shopquick.git
   cd shopquick
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Setup**
   
   Create a `.env.local` file in the root directory:
   ```bash
   # Clerk Authentication
   NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
   CLERK_SECRET_KEY=your_clerk_secret_key
   
   # Database (Neon PostgreSQL)
   DATABASE_URL=your_neon_database_url
   
   # ImageKit
   NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
   IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
   IMAGEKIT_URL_ENDPOINT=your_imagekit_url_endpoint
   
   # Stripe
   NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY=your_stripe_publishable_key
   STRIPE_SECRET_KEY=your_stripe_secret_key
   
   # Inngest
   INNGEST_EVENT_KEY=your_inngest_event_key
   INNGEST_SIGNING_KEY=your_inngest_signing_key
   ```

4. **Database Setup**
   ```bash
   npm run db:push
   npm run db:seed  # Optional: seed with sample data
   ```

5. **Start the development server**
   ```bash
   npm run dev
   ```

6. **Open your browser**
   
   Navigate to [http://localhost:3000](http://localhost:3000) to see the application.

---

## 📁 Project Structure

```
shopquick/
├── app/                    # Next.js App Router
│   ├── (admin)/           # Admin dashboard pages
│   ├── (public)/          # Public storefront pages
│   ├── (vendor)/          # Vendor dashboard pages
│   └── api/               # API routes
├── components/            # Reusable React components
├── lib/                   # Utility functions and configurations
├── public/                # Static assets
├── store/                 # Redux store configuration
├── types/                 # TypeScript type definitions
└── styles/                # Global styles
```

---

## 🔧 Configuration

### Service Setup

1. **Clerk Authentication** - [Sign up here](https://go.clerk.com/YMrJXlT)
   - Create a new application
   - Copy your publishable and secret keys

2. **Neon Database** - [Get started](https://get.neon.com/Fk1Nl7s)
   - Create a new PostgreSQL database
   - Copy your connection string

3. **ImageKit** - [Register here](https://tinyurl.com/58by3zpu)
   - Set up image storage and optimization
   - Configure your endpoint and keys
   - [Documentation](https://tinyurl.com/tnybufw3)

4. **Inngest** - [Learn more](https://innge.st/yt-gs-4)
   - Set up background job processing
   - Configure event handling

---

## 📸 Screenshots

*Add screenshots of your application here to showcase the UI*

---

## 🚀 Deployment

### Deploy to Vercel

1. **Connect your repository**
   ```bash
   # Push your code to GitHub
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Deploy with Vercel**
   - Visit [vercel.com](https://vercel.com)
   - Import your GitHub repository
   - Configure environment variables
   - Deploy!

Your application will be available at your custom Vercel URL.

---

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Make your changes**
4. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
5. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
6. **Open a Pull Request**

Please read our [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed guidelines.

---

## 📋 Roadmap

- [ ] Mobile app development (React Native)
- [ ] Advanced analytics dashboard
- [ ] Multi-language support
- [ ] AI-powered product recommendations
- [ ] Social media integrations
- [ ] Advanced SEO optimizations

---

## 🐛 Known Issues

- [ ] Issue tracking will be managed via GitHub Issues

---

## 📚 Resources & Learning

- [Next.js Documentation](https://nextjs.org/docs)
- [Tutorial Video](https://youtube.com/@GreatStackDev) - Complete build walkthrough
- [Clerk Documentation](https://clerk.com/docs)
- [Neon Documentation](https://neon.tech/docs)
- [ImageKit Documentation](https://docs.imagekit.io/)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE.md) file for details.

---

## 👤 Author

**Ayush Prem**
- GitHub: [@ayushpremrocks](https://github.com/ayushpremrocks)
- Project Link: [https://github.com/ayushpremrocks/shopquick](https://github.com/ayushpremrocks/shopquick)

---

## ⭐ Show Your Support

If this project helped you, please consider giving it a ⭐️ on GitHub!

---

<div align="center">
  <p>Made with ❤️ and lots of ☕</p>
  <p>
    <a href="https://shop-quick-gndt.vercel.app">View Live Demo</a> •
    <a href="https://github.com/ayushpremrocks/shopquick/issues">Report Bug</a> •
    <a href="https://github.com/ayushpremrocks/shopquick/issues">Request Feature</a>
  </p>
</div>
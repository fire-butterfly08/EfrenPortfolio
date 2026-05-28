# Efren's Portfolio Website

A modern, responsive portfolio website showcasing full-stack development skills and projects. Built with Next.js, TypeScript, and Tailwind CSS, featuring smooth animations and a clean, professional design.

## 🚀 Live Demo

[View Live Portfolio](https://efrenportfolio.netlify.app/)

## ✨ Features

- **Responsive Design**: Fully responsive across all devices and screen sizes
- **Dark/Light Mode**: Theme switching with next-themes
- **Smooth Animations**: Powered by Framer Motion for engaging user experience
- **Modern UI Components**: Custom-built components with Tailwind CSS
- **Interactive Elements**: Animated tooltips, buttons, and text effects
- **Skills Section**: Visual representation of technical skills and tools
- **Testimonials**: Client feedback and reviews section
- **Contact Integration**: Direct email contact functionality
- **SEO Optimized**: Built with Next.js for optimal performance and SEO

## 🛠 Tech Stack

### Frontend
- **Next.js 14** - React framework with App Router
- **TypeScript** - Type-safe JavaScript
- **Tailwind CSS** - Utility-first CSS framework
- **Framer Motion** - Animation library
- **Lucide React** - Icon library

### Development Tools
- **ESLint** - Code linting
- **PostCSS** - CSS processing
- **Vercel** - Deployment platform

### Key Dependencies
- `clsx` - Conditional className utility
- `next-themes` - Theme switching
- `react-intersection-observer` - Scroll-based animations
- `tailwind-merge` - Tailwind class merging
- `mini-svg-data-uri` - SVG optimization

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm, yarn, or pnpm

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/fire-butterfly08/EfrenPortfolio.git
   cd portfolio-website
   ```

2. **Install dependencies**
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

3. **Run the development server**
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

4. **Open your browser**
   Navigate to [http://localhost:3000](http://localhost:3000) to see the portfolio.

### Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run start` - Start production server
- `npm run lint` - Run ESLint

## 📁 Project Structure

```
portfolio-website/
├── app/
│   ├── _components/          # Reusable UI components
│   │   ├── ui/              # Base UI components
│   │   ├── HeroSection.tsx  # Hero/landing section
│   │   ├── Skills.tsx       # Skills showcase
│   │   ├── ProjectsSection.tsx
│   │   ├── Testimonials.tsx
│   │   └── Footer.tsx
│   ├── _lib/                # Utilities and constants
│   │   └── constants.ts     # Project data and configurations
│   ├── _styles/             # Global styles
│   ├── layout.tsx           # Root layout
│   └── page.tsx             # Home page
├── public/
│   └── imgs/                # Static images
│       ├── avatars/         # Client avatars
│       ├── logos/           # Technology logos
│       └── projects/        # Project screenshots
├── tailwind.config.ts       # Tailwind configuration
├── next.config.mjs          # Next.js configuration
└── package.json
```

## 🎨 Customization

### Personal Information

Update your personal information in the following files:

1. **Hero Section** (`app/_components/HeroSection.tsx`):
   - Name and title
   - Location
   - Email address
   - Bio description

2. **Constants** (`app/_lib/constants.ts`):
   - Skills and technologies
   - Project portfolio
   - Client testimonials

3. **Package.json**:
   - Author information
   - GitHub profile

### Styling

- **Colors**: Modify the color scheme in `tailwind.config.ts`
- **Fonts**: Update font families in the Tailwind config
- **Components**: Customize component styles in their respective files

### Adding Projects

Add new projects to the `portfolioProjects` array in `app/_lib/constants.ts`:

```typescript
{
  id: "unique-project-id",
  heading: "Project Name",
  subheading: "Brief description",
  description: "Detailed project description",
  imageUrl: "/imgs/projects/project-image.png",
  techStack: ["React", "Node.js", "MongoDB"],
  liveDemoUrl: "http://anomusly.vercel.app/",
  sourceCodeUrl: "https://github.com/fire-butterfly08/efrenfernandez.github.io"
}
```

## 🚀 Deployment

### Vercel (Recommended)

1. Push your code to GitHub
2. Connect your repository to [Vercel](https://vercel.com)
3. Deploy with zero configuration

### Other Platforms

The project can be deployed to any platform that supports Next.js:
- Netlify
- Railway
- DigitalOcean App Platform
- AWS Amplify

## 📧 Contact

**Efren** - Full Stack Developer

- Email: goto.enchanter@gmail.com
- GitHub: [@fire-butterfly08](https://github.com/fire-butterfly08)
- Portfolio: [Live Demo](http://anomusly.vercel.app)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ If you found this portfolio template helpful, please give it a star on GitHub!
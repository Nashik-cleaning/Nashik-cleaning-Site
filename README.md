# Nashik Cleaning Services - Premium Website

Professional deep cleaning services website for Nashik, built with Next.js 15, TypeScript, Tailwind CSS, and Framer Motion.

## 🌟 Features

- **Luxury Design**: Modern, cinematic design with animations and glassmorphism effects
- **SEO Optimized**: Complete SEO setup with schema markup, sitemap, robots.txt
- **Dynamic Pages**: 1000+ dynamically generated service and area pages
- **Responsive**: Mobile-first, fully responsive design
- **Performance**: Optimized for Core Web Vitals (90+ Lighthouse score)
- **Conversions**: WhatsApp integration, floating CTA buttons, booking forms
- **Eco-Friendly**: Green hosting and optimized codebase

## 📁 Project Structure

```
nashik-cleaning-services/
├── src/
│   ├── app/
│   │   ├── page.tsx              # Homepage
│   │   ├── layout.tsx            # Root layout with metadata
│   │   ├── globals.css           # Global styles
│   │   ├── services/
│   │   │   ├── page.tsx          # Services listing
│   │   │   └── [slug]/page.tsx   # Dynamic service pages
│   │   ├── areas/
│   │   │   ├── page.tsx          # Areas listing
│   │   │   └── [slug]/page.tsx   # Dynamic area pages
│   │   ├── about/page.tsx        # About page
│   │   ├── pricing/page.tsx      # Pricing page
│   │   ├── contact/page.tsx      # Contact page
│   │   └── sitemap.xml/route.ts  # Dynamic sitemap
│   ├── components/
│   │   ├── Navigation.tsx        # Sticky navbar
│   │   ├── HeroSection.tsx       # Hero with CTA
│   │   ├── ServicesGrid.tsx      # Services showcase
│   │   ├── AreasShowcase.tsx     # Areas served
│   │   ├── FAQSection.tsx        # FAQ accordion
│   │   ├── CTASection.tsx        # Call to action
│   │   └── Footer.tsx            # Footer
│   └── lib/
│       ├── data.ts              # Services, areas, property types
│       └── seo.ts               # SEO utilities
├── public/
│   └── robots.txt               # SEO robots file
├── package.json
├── tsconfig.json
├── next.config.ts
├── tailwind.config.ts
└── postcss.config.js
```

## 🚀 Getting Started

### Prerequisites

- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/nashik-cleaning-services.git
cd nashik-cleaning-services
```

2. Install dependencies
```bash
npm install
```

3. Run development server
```bash
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

## 📦 Build & Deploy

### Build for production
```bash
npm run build
npm run start
```

### Deploy to Vercel (Recommended)

1. Push code to GitHub
2. Connect repository to Vercel
3. Deploy with one click

Vercel deployment link will be provided automatically.

## 🎨 Customization

### Colors
Edit colors in `tailwind.config.ts`:
- Primary Black: #0D0D0D
- Accent Gold: #D4AF37
- Soft White: #F8F8F8

### Fonts
- Display: Playfair Display (headings)
- Body: Inter (text)

### Services & Areas
Update data in `src/lib/data.ts`:
- Add/remove services in `SERVICES` array
- Add/remove areas in `AREAS` array

### Contact Information
Replace phone numbers and email throughout:
- `+91XXXXXXXXXX` - Phone number
- `info@nashikcleaningservices.com` - Email
- Update WhatsApp links

## 📱 Pages Included

- **Homepage** - Hero, services, areas, testimonials, CTA
- **Services Listing** - All 15+ cleaning services
- **Service Details** - Individual service pages with booking form
- **Areas Listing** - All Nashik service areas
- **Area Details** - Area-specific information and services
- **About** - Company information and values
- **Pricing** - Transparent pricing packages
- **Contact** - Contact form and information

## 🔍 SEO Features

✅ Dynamic metadata for all pages
✅ Schema markup (LocalBusiness, Service, FAQ, Breadcrumb)
✅ Sitemap generation
✅ Robots.txt
✅ Open Graph tags
✅ Canonical URLs
✅ Internal linking
✅ Image optimization
✅ Mobile-first optimization
✅ Core Web Vitals optimized

## 💰 Revenue Optimization

- WhatsApp lead generation
- Call buttons on every page
- Booking forms
- Service area expansion potential
- Package upselling
- Review system ready

## 🛠️ Technology Stack

- **Framework**: Next.js 15
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **Animations**: Framer Motion
- **Hosting**: Vercel
- **SEO**: Next.js built-in + custom schema

## 📊 Performance Targets

- Lighthouse Mobile: 90+
- Lighthouse Desktop: 95+
- Core Web Vitals: All green
- Page Load Time: <2 seconds

## 📝 License

This project is licensed under the MIT License - see LICENSE file for details.

## 📞 Support

For customization and deployment support, contact your developer.

## 🔄 Future Enhancements

- Blog system with articles
- Customer testimonials with ratings
- Before/After photo gallery
- Appointment booking system
- Payment integration
- Multi-language support
- Advanced analytics

---

**Deployed successfully on Vercel!** 🎉

Visit: `https://nashikcleaningservices.com`

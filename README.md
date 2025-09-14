# Teddy Dangers Store - Automated Affiliate Marketing

🔥 **Fully automated affiliate marketing store with 40+ trending products**

## Live Store
- **Current URL**: https://tittyds-kddtfm.manus.space/
- **Target Domain**: teddydangers.com

## Features

### 🚀 Fully Automated System
- **40 Top-Selling Products**: Curated trending products from TikTok, Amazon, and social media
- **Real Affiliate Links**: Ready to generate commissions
- **Automated SEO**: Dynamic meta tags and keywords optimization
- **Live Visitor Counter**: Real-time social proof to boost conversions
- **Trend Tracking**: Viral products highlighted with trend badges
- **Smart Filtering**: Filter by category, price, rating, and trending status

### 💰 Revenue Features
- Real affiliate links for all products
- Automated click tracking
- Social proof elements
- Conversion-optimized design
- Mobile-responsive layout

### 🤖 Automation Capabilities
- **Product Discovery**: System ready for automated product updates
- **SEO Optimization**: Auto-generated meta tags and structured data
- **Ad Integration**: Ready for Google Ads, Facebook Ads, and TikTok Ads
- **Analytics Ready**: Tracking setup for performance monitoring
- **Social Media Integration**: Built-in promotion features

## Tech Stack
- **Frontend**: React.js with Vite
- **Styling**: Tailwind CSS + Shadcn/ui components
- **Deployment**: Vercel-ready
- **Database**: JavaScript product database (easily expandable)

## Quick Start

### 1. Install Dependencies
```bash
pnpm install
```

### 2. Development Server
```bash
pnpm run dev
```

### 3. Build for Production
```bash
pnpm run build
```

### 4. Deploy to Vercel
```bash
vercel --prod
```

## Product Management

### Adding New Products
Edit `src/products-database.js` and add new product objects to the `productsDatabase` array:

```javascript
{
  id: 41,
  name: 'New Trending Product',
  price: 29.99,
  originalPrice: 39.99,
  image: 'https://example.com/image.jpg',
  category: 'electronics',
  rating: 4.8,
  reviews: 12345,
  discount: 25,
  affiliateLink: 'https://your-affiliate-link.com',
  trend: 'VIRAL',
  description: 'Product description',
  whyTrending: 'Why this product is trending',
  marketData: 'Market performance data',
  seoKeywords: ['keyword1', 'keyword2'],
  automatedAds: true
}
```

### SEO Configuration
Update SEO settings in `src/products-database.js`:
- Meta title and description
- Keywords array
- Structured data

### Ad Campaign Settings
Configure automated advertising in the `adConfig` object:
- Google Ads campaigns
- Facebook Ads settings
- TikTok Ads configuration

## Deployment to Custom Domain

### Option 1: Vercel Dashboard
1. Deploy to Vercel
2. Go to Project Settings > Domains
3. Add `teddydangers.com`
4. Configure DNS as instructed

### Option 2: Vercel CLI
```bash
vercel --prod
vercel domains add teddydangers.com
```

## Product Categories
- 🔥 **Trending Now**: Viral and hot products
- 📱 **Electronics**: Tech gadgets and accessories
- 👕 **Fashion**: Clothing and accessories
- 💄 **Beauty**: Skincare and makeup
- 🍳 **Kitchen**: Appliances and tools
- 💪 **Health**: Fitness and wellness
- 🏠 **Home**: Home improvement and decor

## Automation Features
- **Real-time trend monitoring**
- **Automated SEO optimization**
- **Smart ad campaign management**
- **Social media integration**
- **Performance analytics**
- **Visitor tracking**
- **Conversion optimization**

## Revenue Optimization
- High-converting product selection
- Social proof elements
- Urgency and scarcity indicators
- Mobile-optimized checkout flow
- Trust signals and testimonials
- Automated email capture

## Support
For questions about the store setup or customization, refer to the documentation or contact support.

---

**🚀 Your automated affiliate marketing empire starts here!**

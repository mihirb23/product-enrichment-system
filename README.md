# AI Product Hub

An intelligent product enrichment platform that automatically categorizes and enriches e-commerce products using OpenAI's GPT-3.5-turbo API.

## Live Demo
[https://product-enrichment-system-a049avqpy-mihirs-projects-8d452b92.vercel.app/](https://product-enrichment-system-a049avqpy-mihirs-projects-8d452b92.vercel.app/)

## 📋 What It Does
Transform basic product information (name + brand) into fully categorized products with:
- **Product Categories** (Sports & Recreation, Electronics, Health & Supplements, etc.)
- **Google Shopping Categories** (detailed hierarchical categories)
- **Custom Attributes** (weight, dimensions, materials, etc.)

## Key Features

### Product Management
- **Smart Filters**: Hide/show filters, search by category, status, date range
- **Bulk Operations**: CSV import, multi-select enrichment
- **AI Enrichment**: One-click categorization using OpenAI
- **CRUD Operations**: Add, edit, copy, delete products

### Attribute Management  
- **Custom Attributes**: Create attributes with AI enrichment
- **Home Areas**: Kitchen, Bathroom, Living Room, etc.
- **AI Prompts**: Configure custom prompts for each attribute
- **Bulk Selection**: Select multiple attributes for batch operations

## AI Examples
Input: "Football" by "Nike"
Output: Sports & Recreation | Sporting Goods > Team Sports > Football

Input: "Protein Powder" by "Optimum Nutrition"
Output: Health & Supplements | Health & Personal Care > Vitamins & Dietary Supplements

Input: "Wireless Headphones" by "AudioTech"
Output: Electronics | Electronics > Audio > Audio Components > Headphones

## Tech Stack
- **Frontend**: React 18 + TypeScript
- **AI**: OpenAI GPT-3.5-turbo API
- **Icons**: Lucide React
- **Deployment**: Vercel
- **Styling**: Custom CSS

## Deployment
- **Production**: Deployed on Vercel with automatic GitHub integration
- **Environment**: OpenAI API key configured in Vercel dashboard



This is a [Next.js](https://nextjs.org) project bootstrapped with [`create-next-app`](https://nextjs.org/docs/app/api-reference/cli/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
# product-enrichment-system

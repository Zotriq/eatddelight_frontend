# Daughter's Delight: Online Storefront

![Next.js](https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-State-443E38?style=flat-square)

Front end for **Daughter's Delight**, a home-kitchen food business that used to take every order by Instagram DM
and phone. Customers can now browse the menu, build a cart and send a ready-made order on WhatsApp.

## Features

**Storefront**
- Home page, **Menu of the Day** (one dish per weekday) and the full à la carte menu with search and category filters
- Food detail pages, quick-view modal and favourites
- Cart saved in the browser, with checkout that opens a pre-filled WhatsApp order (no accounts or online payment needed)
- Custom-order and contact forms
- SEO: sitemap, robots.txt and app icons

**Experience**
- Smooth scrolling (Locomotive Scroll), GSAP animations and page transitions
- Responsive, mobile-first design

## Getting started

```bash
npm install
npm run dev     # http://localhost:3000
```

Set the backend API URL in `.env.local`:

```env
NEXT_PUBLIC_API_URL=http://localhost:8000/api/v1
```

## Tech stack

Next.js (App Router) · TypeScript · Tailwind CSS · Zustand · GSAP · Locomotive Scroll · lucide-react

# CRM + Dashboard for E-Commerce Store

This is a repository for CRM + Dashboard for E-Commerce Store: Next.js 13.4, React, TailwindCSS, Stripe, ShadCN UI, MySQL, AWS.

Key Features:

- It serves as both CRM as well as Admin Dashboard, also provides API for quick development
- Mulitple vendors / stores can be controlled through this single CMS!
- Create, update and delete categories, products, billboards, colors & sizes
- Upload multiple images for products, and change them whenever required
- Search through all categories, products, sizes, colors, billboards with included pagination
- Control which products are needed to be "Featured"
- Total Orders, Sales, Revenue, Stocks are displayed on Admin Dashboard.
- Graphs of your Revenue per Month
- MySQL database deployed on AWS
- Stripe Webhook for Orders Confirmation
- Zustand for State Management
- Credential authentication with Clerk
- Google authentication with Clerk
- Client form validation and handling using react-hook-form
- Server error handling with react-hot-toast
- Tailwind design for sleek UI
- Tailwind animations and transition effects
- Full responsiveness for all devices

# Final Version

To visit the website, [click here.](https://admin-dashboard-ss.vercel.app)

## USE THIS WITH [ECOMMERCE WEBSITE](https://github.com/ShethSamarth/ecommerce-store)

### Cloning the repository

```shell
git clone https://github.com/ShethSamarth/admin-dashboard.git
```

### Install packages

```shell
npm install
```

### Setup prisma

```shell
npx prisma generate
npx prisma db push
```

### Setup .env file

```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=

NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

DATABASE_URL=

NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=

STRIPE_API_KEY=
STRIPE_WEBHOOK_SECRET=

FRONTEND_STORE_URL=

```

### Start the app

```shell
npm run dev
```

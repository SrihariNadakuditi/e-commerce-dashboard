# Full Stack E-Commerce + Dashboard: Next.js 13 App Router, React, Tailwind, Prisma, Mysql




## Key Features

- **Dashboard**: Seamlessly integrates CMS, Admin, and API functionalities.
- **Multi-Vendor Control**: Operate various types of stores like "Shoe store", "Laptop store", and "Suit store".
- **Dynamic API Route Generation**: Each store gets its individual API route for easy integration.
- **Category Management**: Create, modify, and remove product categories with ease.
- **Product Management**: Add, update, or delete products effortlessly.
- **Image Management**: Upload multiple product images, replace them as needed.
- **Filter Management**: Define attributes like "Color" and "Size". Link these filters during product creation.
- **Billboard Management**: Craft attention-grabbing headers for your pages. Attach them to specific categories or display them standalone.
- **Advanced Search**: Search categories, products, sizes, colors, billboards with built-in pagination.
- **Homepage Curation**: Designate "featured" products for prominent homepage display.
- **Sales Insights**: Track orders, sales, and other crucial business metrics.
- **Data Visualization**: Graphical representation of revenue trends and other data.
- **Secure Authentication**: Implement Clerk Authentication for secure user access.
- **Order Handling**: Simplified order creation for a smooth user experience.
- **Seamless Payments**: Integrated Stripe checkout for easy payments.
- **Stripe Webhooks**: Automated notifications for Stripe events.
- **Reliable Database Solution**: Powered by MySQL, Prisma, and Cockroachdb.

## 🚀 Getting Started


### Prerequisites

**Node version 14.x**

### Cloning the repository

```shell
git clone 
```

### Install packages

```shell
npm i
```

### Setup .env file


```js
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_AFTER_SIGN_IN_URL=/
NEXT_PUBLIC_CLERK_AFTER_SIGN_UP_URL=/

# This was inserted by `prisma init`:
# Environment variables declared in this file are automatically made available to Prisma.
# See the documentation for more detail: https://pris.ly/d/prisma-schema#accessing-environment-variables-from-the-schema

# Prisma supports the native connection string format for PostgreSQL, MySQL, SQLite, SQL Server, MongoDB and CockroachDB.
# See the documentation for all the connection string options: https://pris.ly/d/connection-strings

DATABASE_URL=''
NEXT_PUBLIC_CLOUDINARY_CLOUD_NAME=""
STRIPE_API_KEY=
FRONTEND_STORE_URL=http://localhost:3001
STRIPE_WEBHOOK_SECRET=
```

- you can visit the store here :https://e-commerce-c6x8.vercel.app/
- github repository: https://github.com/SrihariNadakuditi/e-commerce-store
- deployment link: https://e-commerce-six-liard.vercel.app/sign-in?redirect_url=https%3A%2F%2Fe-commerce-six-liard.vercel.app%2F


### Connect to Cockroachdb and Push Prisma
```shell
npx prisma generate
npx prisma db push
```


### Start the app

```shell
npm run dev
```

## Available commands

Running commands with npm `npm run [command]`

| command         | description                              |
| :-------------- | :--------------------------------------- |
| `dev`           | Starts a development instance of the app |

# Svelte Pokopia Image Rater

## Setup

### 1. Install Dependencies

```sh
npm install
```

### 2. Configure Environment

Copy `.env.example` to `.env` and configure:

- TODO: Check DATABASE_URL in .env and adjust it to your needs
- TODO: Check ORIGIN & BETTER_AUTH_SECRET in .env and adjust them to your needs

### 3. Setup Database (Drizzle)

```sh
# Update your database schema
npm run db:push
```

### 4. Setup Authentication (Better Auth)

```sh
# Generate the auth schema
npm run auth:schema

# Update your database with auth tables
npm run db:push
```

### 5. Verify Setup

- TODO: Visit `/demo/better-auth` route to view the demo

## Running the Application

Start the development server:

```sh
npm run dev

# or open in browser automatically
npm run dev -- --open
```

Build for production:

```sh
npm run build
npm run preview
```

## Documentation

- [SvelteKit](https://svelte.dev/docs/kit)
- [Better Auth](https://www.better-auth.com/docs)
- [Drizzle ORM](https://orm.drizzle.team/docs/overview)
- [TailwindCSS](https://tailwindcss.com/docs)

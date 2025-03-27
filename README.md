## Features

- **Modern Components & Layouts** – Includes built-in components.
- **Nuxt UI v3** – Utilize pre-built, customizable UI components.
- **NuxtHub ready** - Deploy on NuxtHub in seconds.
- **Tailwind CSS** – A beautiful, responsive design system.
- **Working Contact Form** – Integrated with Resend for easy email handling.
- **Multi-language Support** – Powered by Nuxt i18n.
- **SEO-Ready** – Open Graph Image (Nuxt OG Image) & Nuxt Robots for automatic robots.txt generation.
- **Good practices** – Auto-generated sitemap, optimized images (Nuxt Image), and ESLint (Nuxt config with Flat config).
- **Fully Responsive** – Adapts to all modern browsers and devices.
- **Minimal & Professional Design** – Clean, elegant, and easy to customize.

## Quick Setup

1. Clone this repository if you have access or download it from the store

```bash
git clone git@github.com:Vldln/Intersubjective/intersubjective-website.git
```

2. Install dependencies

```bash
pnpm install
```

3. Copy the `.env.example` file to `.env` and fill in the values

```bash
cp .env.example .env
```

4. Start development server

```bash
pnpm dev
```

5. Generate static project

```bash
pnpm generate
```

6. Start production server

```bash
pnpm start
```

## Deployments

### Nuxt Studio [https://nuxt.studio/](https://nuxt.studio/)

Allow edit content, but dont work with ssr. Its mean server routes with email forms dont work.

### Vercel [https://vercel.com/](https://vercel.com/)

Allow work app ssr. Better for main deploy.

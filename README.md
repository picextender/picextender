# PicExtender - AI Image Extender, Enhancer, and Photo Restoration

![PicExtender Preview](https://picextender.com/preview.png)

## About This Project

Welcome to **PicExtender**, an AI-powered image editing platform for expanding images, improving photo quality, restoring old photos, and preparing visuals for social media, ecommerce, ads, and archives.

This project powers [picextender.com](https://picextender.com/), a web app focused on fast upload-first image workflows. Users can expand image borders with AI outpainting, resize images for platform-specific formats, edit images with prompts, enhance blurry or low-resolution photos, and restore damaged vintage photos.

## Core Tools

PicExtender includes focused tools for common creative and publishing workflows:

* **AI Image Extender** - Expand image borders naturally without stretching or hard cropping.
* **Batch Image Extender** - Upload multiple images and generate consistent output sizes in one workflow.
* **AI Image Editor** - Edit uploaded images with plain-language prompts.
* **Photo Enhancer** - Improve clarity, reduce noise, fix blur, and upscale images.
* **Photo Restoration** - Repair scratches, stains, fading, tears, blur, and colorize old photos.
* **Platform Resizers** - Create ready-to-publish images for YouTube, Instagram, Pinterest, Facebook, LinkedIn, and Twitter/X.

## Features

* **AI outpainting** - Generate realistic new image areas from the source image context.
* **Platform-ready presets** - Fit common social and ad sizes without losing the subject.
* **Up to 4K output** - Export expanded canvases up to 4096 x 4096 px.
* **Batch processing** - Standardize a full image set for product listings, campaigns, and content libraries.
* **Prompt-based editing** - Replace backgrounds, refine scenes, adjust style, or remove distractions.
* **Photo enhancement** - Make blurry, noisy, compressed, or low-resolution images clearer.
* **Old photo repair** - Restore damaged family photos and colorize black-and-white images.
* **Responsive experience** - Built for desktop and mobile upload workflows.
* **Multi-language support** - Localized pages and app UI powered by next-intl.
* **Credits and billing** - User accounts, credits, checkout, and payment integrations.

## Visit the Website

**Website:** <https://picextender.com/>

Use PicExtender to:

* Expand images for social media and ad formats.
* Resize images without cropping important subjects.
* Edit images from a text prompt.
* Enhance portraits, product photos, and everyday images.
* Restore and colorize old family photos.
* Batch process multiple images for repeatable output.

## Technology Stack

* **Next.js 16** - App Router, server components, routing, and production builds.
* **React 19** - Interactive UI and tool workflows.
* **TypeScript** - Type-safe application code.
* **Tailwind CSS 4** - Styling and responsive layout.
* **next-intl** - Internationalization and localized routes.
* **Better Auth** - Authentication and account management.
* **Drizzle ORM** - Database schema and migrations.
* **PostgreSQL / MySQL / SQLite** - Configurable database support.
* **Stripe, PayPal, and Creem** - Payment provider integrations.
* **Replicate, Gemini, Fal, Kie, and NewAPI** - AI provider extension layer.
* **Cloudflare / OpenNext** - Cloudflare deployment support.

## SEO Features

* Search-friendly landing pages for each image workflow.
* Localized metadata for supported languages.
* XML sitemap and robots configuration.
* Open Graph preview image support.
* Clean page titles and descriptions.
* Fast responsive pages built with Next.js.
* Structured content sections for tools, use cases, FAQs, pricing, and calls to action.

## How to Use

1. **Open PicExtender:** Visit [picextender.com](https://picextender.com/).
2. **Choose a tool:** Select AI Image Extender, Batch Extender, Image Editor, Photo Enhancer, or Photo Restoration.
3. **Upload an image:** Supported formats include JPG, JPEG, PNG, and WEBP.
4. **Pick an output:** Choose a preset, custom size, enhancement mode, restoration mode, or edit prompt.
5. **Generate the result:** Let AI expand, edit, enhance, or restore the image.
6. **Download the final image:** Export a ready-to-use visual for publishing, sharing, or archiving.

## Local Development

Install dependencies:

```bash
pnpm install
```

Start the development server:

```bash
pnpm dev
```

Build for production:

```bash
pnpm build
```

Run database migrations:

```bash
pnpm db:migrate
```

## Environment Configuration

Common environment values include:

* `NEXT_PUBLIC_APP_URL` - Public app URL.
* `NEXT_PUBLIC_APP_NAME` - Application name.
* `NEXT_PUBLIC_APP_LOGO` - Logo path.
* `NEXT_PUBLIC_DEFAULT_LOCALE` - Default locale.
* `DATABASE_PROVIDER` - Database provider.
* `DATABASE_URL` - Database connection URL.
* `AUTH_SECRET` - Authentication secret.
* `DB_TABLE_PREFIX` - Optional table prefix for shared databases.

Review `.env.example` for the full configuration surface before deployment.

## Quick Links

* [AI Image Extender](https://picextender.com/)
* [Batch Image Extender](https://picextender.com/batch-extender)
* [AI Image Editor](https://picextender.com/image-editor)
* [Photo Enhancer](https://picextender.com/photo-enhancer)
* [Photo Restoration](https://picextender.com/photo-restoration)
* [YouTube Thumbnail Resizer](https://picextender.com/youtube-thumbnail-resizer)
* [Instagram Image Resizer](https://picextender.com/resize-image-for-instagram)

## Contributing

This project is maintained as the PicExtender web application. Contributions should stay aligned with the existing Next.js, TypeScript, Tailwind CSS, i18n, and service-extension patterns already used in the codebase.

Before submitting changes:

1. Run formatting and lint checks.
2. Verify the affected image workflow locally.
3. Add or update localized content when changing user-facing copy.
4. Confirm SEO metadata for any new public page.

## License

Copyright 2026 PicExtender. All rights reserved.

Product names, logos, and third-party services remain the property of their respective owners.

---

Visit **[picextender.com](https://picextender.com/)** to expand, edit, enhance, and restore images with AI.

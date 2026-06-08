<!-- readme-hero -->
<div align="center">

<img src="assets/readme-hero.svg" alt="CAROUSEL GENERATOR" width="100%" />

</div>

# Carousel Generator

**Carousel Generator** is an open-source carousel generator tool that allows you to easily create and customize carousels for your LinkedIn.

🔗 [Website](https://carouselgenerator.vercel.app)

## AI Demo

https://github.com/FranciscoMoretti/carousel-generator/assets/16997807/50cb033d-84d5-4214-93aa-45c6f524d0b1

## Features

Carousel Generator comes packed with a variety of features to help you create stunning carousels effortlessly:

- 🪄 Generate carousels with AI
- ✍️ Forms powered by [react-hook-form](https://react-hook-form.com/)
- 🎨 Sleek UI components from [Shadcn/ui](https://ui.shadcn.com/)
- ✅ Input validation using [ZOD](https://zod.dev/)
- 🌐 Responsive layout for various screen sizes
- 🔄 Automatic updates on changes
- 🍥 Icons from [Lucide Dev](https://lucide.dev/)
- 🆎 Titles auto-balance (no orphan words)
- 💾 Data persists with browser refresh
- ⚙️ Configure the carousel with various settings
- ➕ Add, remove, or reorder slides with ease
- 🖼️ Different types of slides, including Intro, Content, and Outro
- 📤 Export and Import settings
- 📥 Export and import slide content
- 😃 Support for emojis to spark joy with your carousels
- 📝 Select fonts for titles and content to match your style

## Usage

1. Visit [carouselgenerator.vercel.app](https://carouselgenerator.vercel.app) to access the Carousel Generator tool.

2. Customize your carousel settings and add/edit slides as needed.

3. Download your carousel to post on social media

## Installation

To get started with Carousel Generator, follow these simple installation steps:

1. Create your environment file

   ```bash
   cp .env.example .env
   ```

2. Install the required dependencies using `pnpm`:

   ```bash
   pnpm i
   ```

   or

   ```bash
   npm install
   ```

3. Create the environment variables file:

   ```bash
   cp .env.example .env.local
   ```

   and update the values in the `.env.local` file.

   To get an OpenaI API key, use [your OpenAI API key](https://platform.openai.com/account/api-keys)

   Rate limiting is optional. To enable it, you'll need [Vercel KV credentials](https://vercel.com/docs/storage/vercel-kv/quickstart#quickstart)

   NOTE: Remember to include these environment variables on your server if you are deploying this application.

4. Start the development server:

   ```bash
   pnpm dev
   ```

   or

   ```bash
   npm run dev
   ```

Now you're all set to start using Carousel Generator!

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy carousel generating! If you have any questions or need assistance, feel free to [open an issue](https://github.com/FranciscoMoretti/carousel-generator/issues) on GitHub.

🚀 Thank you for using Carousel Generator!

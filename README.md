# Tachan - Car Marketplace
Site - https://www.tachan.co/

Modern car marketplace built with Next.js 14, featuring a sleek design and powerful functionality.

## Features

- 🚗 Modern car listings with advanced filtering
- 💜 Favorite cars functionality
- 🔍 Smart search with multiple parameters
- 🏷️ Special highlighting for TOP listings
- 🖼️ Optimized image loading and caching
- 🔒 Secure authentication system
- 📱 Fully responsive design
- ⚡️ Server-side rendering for optimal performance

## Tech Stack

- **Framework**: Next.js 14 with App Router
- **Styling**: Tailwind CSS
- **UI Components**: Custom components with modern design
- **Authentication**: NextAuth.js
- **Database**: MongoDB
- **Image Storage**: AWS S3
- **State Management**: Zustand
- **Form Handling**: React Hook Form
- **Validation**: Zod
- **HTTP Client**: Axios

## Getting Started

1. Clone the repository
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   ```env
   DATABASE_URL=your_mongodb_url
   NEXTAUTH_SECRET=your_secret
   AWS_ACCESS_KEY_ID=your_aws_key
   AWS_SECRET_ACCESS_KEY=your_aws_secret
   AWS_REGION=your_aws_region
   AWS_BUCKET_NAME=your_bucket_name
   ```
4. Run the development server:
   ```bash
   npm run dev
   ```

## Project Structure

- `app/` - Next.js app router pages and layouts
- `components/` - Reusable UI components
- `lib/` - Utility functions and configurations
- `models/` - Database models and schemas
- `public/` - Static assets
- `styles/` - Global styles and Tailwind configuration

## Contributing

Feel free to contribute to this project. Open a PR or issue for any improvements.

## License

MIT License

---

Built with ❤️ using Next.js and modern web technologies.

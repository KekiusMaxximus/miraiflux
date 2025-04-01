# MiRAi - AI Automation Agency Website

A modern, responsive website for MiRAi, an AI automation agency built with React, TypeScript, and Tailwind CSS. The site features a beautiful particle animation background, multi-language support, and a contact form with Supabase integration.

![MiRAi Website](https://images.unsplash.com/photo-1451187580459-43490279c0fa?auto=format&fit=crop&q=80&w=1200&h=630)

## Features

- 🎨 Modern UI with particle animations and smooth transitions
- 🌐 Multi-language support (English, Spanish, Italian)
- 📱 Fully responsive design
- 📝 Contact form with Supabase backend
- 🔒 Row Level Security for data protection
- ⚡ Built with Vite for optimal performance

## Tech Stack

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Supabase
- i18next
- React Router
- Lucide Icons

## Getting Started

1. Clone the repository
```bash
git clone https://github.com/yourusername/miraiflux.git
cd miraiflux
```

2. Install dependencies
```bash
npm install
```

3. Set up environment variables
Create a `.env` file in the root directory with your Supabase credentials:
```env
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key
```

4. Start the development server
```bash
npm run dev
```

5. Build for production
```bash
npm run build
```

## Project Structure

```
├── public/
│   └── locales/          # Translation files
├── src/
│   ├── components/       # React components
│   ├── pages/           # Page components
│   ├── lib/             # Utility functions
│   └── i18n/            # i18n configuration
└── supabase/
    └── migrations/      # Database migrations
```

## Database Schema

The project uses Supabase with the following schema:

- `contact_submissions` table
  - `id`: UUID (Primary Key)
  - `created_at`: Timestamp
  - `name`: Text
  - `email`: Text
  - `service`: Text
  - `company_name`: Text
  - `problems`: Text
  - `additional_info`: Text (Optional)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

MiRAi - [@NexMiRAi](https://x.com/NexMiRAi)

Project Link: [https://miraiflux.com](https://miraiflux.com)

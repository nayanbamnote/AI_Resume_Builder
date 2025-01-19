# AI Resume Builder

A modern web application that helps users create professional resumes with AI-powered assistance. Built with React, Vite, and integrated with AI capabilities.

## Features

- 🤖 AI-powered content generation for resume sections
- 📝 Interactive resume builder with real-time preview
- 🎨 Customizable resume themes and colors
- 📱 Responsive design for all devices
- 🔒 Secure authentication with Clerk
- 💾 Save and manage multiple resumes
- 📤 Export resumes to PDF
- 🔗 Share resumes via unique URLs

## Tech Stack

- **Frontend Framework:** React + Vite
- **Styling:** Tailwind CSS + shadcn/ui components
- **Authentication:** Clerk
- **AI Integration:** Google Generative AI (Gemini)
- **State Management:** React Context
- **API Integration:** Axios
- **Routing:** React Router DOM
- **Rich Text Editing:** react-simple-wysiwyg
- **PDF Generation:** react-to-pdf
- **Sharing:** react-web-share

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn
- Environment variables setup

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd ai-resume-builder
```

2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory with the following variables:
```env
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_GOOGLE_AI_API_KEY=your_gemini_api_key
VITE_API_BASE_URL=your_api_base_url
VITE_STRAPI_API_KEY=your_strapi_key
VITE_BASE_URL=your_base_url
```

4. Start the development server:
```bash
npm run dev
```

## Project Structure

```
src/
├── components/         # Reusable UI components
├── dashboard/         # Dashboard related components
├── home/             # Home page components
├── context/          # React context providers
├── service/          # API and service integrations
├── lib/              # Utility functions
└── assets/           # Static assets
```

## Features in Detail

### Resume Builder
- Personal Details
- Professional Summary (AI-assisted)
- Work Experience
- Education
- Skills
- Real-time Preview

### AI Integration
- Generate professional summaries
- Work experience suggestions
- Skills recommendations
- Context-aware content generation

### Customization
- Theme colors
- Layout options
- Font styles
- Section arrangement

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- [Clerk](https://clerk.dev/) for authentication
- [shadcn/ui](https://ui.shadcn.com/) for UI components
- [Google Generative AI](https://ai.google.dev/) for AI capabilities
- [Tailwind CSS](https://tailwindcss.com/) for styling
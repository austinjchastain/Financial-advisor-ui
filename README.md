# Financial-advisor-ui
Financial advisor ui
### AI Financial Planner Interface

An Apple-inspired financial planning application with a clean, modern UI designed for mobile-first experiences.

## Overview

The AI Financial Planner is a user-friendly application that helps users manage their finances through personalized advice and interactive planning tools. The interface follows Apple's design principles with a focus on simplicity, clarity, and depth.

## Features

- **Clean, Apple-inspired UI**: Minimalist design with iOS-style components
- **Mobile-first**: Optimized for mobile devices with responsive design
- **Bottom Navigation**: iOS-style tab bar for easy navigation
- **Financial Dashboard**: Visualize financial health with clean, informative cards
- **Interactive Chat**: Guided financial planning through conversational interface
- **Personalized Results**: Custom financial recommendations based on user inputs


## Pages

1. **Home**: Landing page with app introduction and get started button
2. **Intake Form**: Comprehensive form to collect financial information
3. **Chat Flow**: Series of guided conversations to gather financial preferences
4. **Results Dashboard**: Personalized financial plan with actionable insights


## Tech Stack

- **Framework**: Next.js
- **Styling**: Tailwind CSS
- **Icons**: Lucide React
- **UI Components**: Custom shadcn/ui inspired components


## Installation

1. Clone the repository:


```shellscript
git clone https://github.com/yourusername/ai-financial-planner.git
cd ai-financial-planner
```

2. Install dependencies:


```shellscript
npm install
```

3. Run the development server:


```shellscript
npm run dev
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser


## Project Structure

```plaintext
ai-financial-planner/
├── app/
│   ├── layout.tsx        # Root layout with bottom navigation
│   ├── page.tsx          # Home/landing page
│   ├── intake/           # Financial information intake form
│   ├── chat/             # Guided conversation flow
│   ├── results/          # Financial results dashboard
│   └── globals.css       # Global styles
├── components/
│   ├── bottom-nav.tsx    # iOS-style bottom navigation
│   └── ui/               # Reusable UI components
├── public/               # Static assets
└── README.md             # Project documentation
```

## Design Principles

- **Clean Typography**: System fonts with careful hierarchy
- **Whitespace**: Generous spacing for readability
- **Color Usage**: Strategic use of Apple's color palette
- **Depth**: Subtle shadows and layering
- **Accessibility**: High contrast and readable text


## Future Enhancements

- Dark mode support
- Interactive charts and graphs
- Face ID/Touch ID authentication
- Home screen widgets
- Push notification system


## License

MIT

---


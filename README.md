# Cosmic Explorer: Interactive Solar System

![Cosmic Explorer Preview](./generated-icon.png)

An interactive and immersive web application designed to educate users about the solar system through engaging 3D visualizations, educational content, and interactive learning experiences.

## ✨ Features

- **Interactive 3D Solar System**: Explore planets in an immersive 3D environment powered by Three.js
- **Detailed Planet Information**: Learn about each planet's composition, exploration history, and key characteristics
- **Educational Quiz System**: Test your knowledge with space-themed quizzes
- **Fun Facts Section**: Discover interesting astronomy facts
- **Explore More Content**: Additional educational resources and space exploration content

## 🚀 Tech Stack

- **Frontend**: React, TypeScript, Vite
- **3D Rendering**: Three.js
- **Styling**: Tailwind CSS, shadcn/ui
- **Animation**: Framer Motion
- **State Management**: React Context API, TanStack Query
- **Icons**: Remixicon, Lucide React
- **Routing**: Wouter

## 📋 Prerequisites

- Node.js 18+
- npm or yarn

## 🛠️ Installation

1. Clone the repository
   ```bash
   git clone https://github.com/your-username/cosmic-explorer.git
   cd cosmic-explorer
   ```

2. Install dependencies
   ```bash
   npm install
   # or
   yarn install
   ```

3. Start the development server
   ```bash
   npm run dev
   # or
   yarn dev
   ```

4. Open your browser and navigate to `http://localhost:3000`

## 🔍 Project Structure

```
cosmic-explorer/
├── client/              # Frontend source code
│   ├── src/
│   │   ├── components/  # UI components
│   │   ├── contexts/    # React context providers
│   │   ├── hooks/       # Custom React hooks
│   │   ├── lib/         # Utility functions
│   │   ├── pages/       # Page components
│   │   └── styles/      # CSS and styling
├── server/              # Backend source code
│   ├── index.ts         # Server entry point
│   ├── routes.ts        # API routes
│   └── storage.ts       # Data storage layer
├── shared/              # Shared code between frontend and backend
│   └── schema.ts        # Data models and validation schemas
└── ...                  # Configuration files
```

## 🎮 Usage

- Navigate through the solar system using your mouse
- Click on planets to view detailed information
- Take quizzes to test your astronomy knowledge
- Explore fun facts and additional educational content

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👏 Acknowledgements

- NASA for planetary data and imagery
- [Three.js](https://threejs.org/) for 3D rendering capabilities
- [shadcn/ui](https://ui.shadcn.com/) for UI components
- All open-source projects that made this application possible
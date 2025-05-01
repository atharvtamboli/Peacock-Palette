# 🦚 Peacock Palette Generator

A beautiful and intuitive color palette generator inspired by the vibrant colors of peacock feathers.

![Peacock Palette Generator Screenshot](screenshot.png)

## Features

- 🎨 Generate harmonious color palettes based on your selected colors
- 🦚 Interactive peacock animation with expandable display
- 💾 Save your favorite color combinations for future use
- 📤 Export palettes as JSON for use in your design projects
- 🌓 Dark mode support for comfortable viewing in any lighting
- 📋 Quick copy-to-clipboard functionality for color codes
- 🔄 "Inspire Me" feature with peacock-inspired color suggestions

## Demo

[View Live Demo](https://yourwebsite.com/peacock-palette) (Replace with your actual demo link when deployed)

## Installation

### Prerequisites

- Node.js (v14.0.0 or higher)
- npm or yarn

### Setup Instructions

1. Clone the repository:
```bash
git clone https://github.com/yourusername/peacock-palette.git
cd peacock-palette
```

2. Install dependencies:
```bash
npm install
# or
yarn install
```

3. Start the development server:
```bash
npm start
# or
yarn start
```

4. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

## Usage

### Creating a Color Palette

1. Select your base colors using the color pickers in the "Feather Colors" section
2. Add or remove base colors using the + and - buttons (maximum 5 colors)
3. Click "Inspire Me" to get random peacock-inspired color suggestions
4. Your generated palette will appear in the section below

### Managing Palettes

- **Save Palette**: Click the "Save Palette" button to store your current palette
- **Export**: Click the "Export" button to download your palette as a JSON file
- **View Saved**: Navigate to the "Saved Palettes" tab to see your collection
- **Load**: Click the eye icon on a saved palette to load it back into the editor
- **Delete**: Use the trash icon to remove a saved palette

### Tips for Creating Great Palettes

- Start with 2-3 base colors for more cohesive results
- Use the "Inspire Me" feature to discover peacock-inspired combinations
- For web design, consider including light and dark variants of your main colors
- Export your palettes to share with team members or use across different design tools

## Technologies Used

- React.js
- Lucide React (for icons)
- Local Storage (for saving palettes)

## Project Structure

```
src/
├── components/
│   └── PeacockPaletteGenerator.jsx  # Main component
├── App.js                           # Application entry point
├── index.js                         # React DOM rendering
└── index.css                        # Global styles
```

## Customization

### Adding Custom Color Presets

You can modify the `randomizePalette` function in `PeacockPaletteGenerator.jsx` to include your own color presets:

```javascript
const peacockColors = [
  // Add your custom colors here
  '#3498db', '#2ecc71', '#9b59b6', 
  // ...
];
```

### Modifying the Peacock Animation

The peacock animation is created using CSS and HTML elements. You can adjust its appearance in the rendering section of the component.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgements

- Peacock illustrations and animations created with CSS
- Color theory principles applied from various design resources
- Icon set provided by [Lucide](https://lucide.dev/)

---

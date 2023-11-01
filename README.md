# Confetti Everything 🎉

Confetti Everything is an npm package for JavaScript that lets you add a fun and colorful touch to your web projects by firing confetti of "everything." With this package, you can use images, gifs, and even components as confetti, giving you the freedom to celebrate and create unique and exciting visual effects.

## Installation

To get started with Confetti Everything, follow these simple steps to install the package:

```bash
npm install confetti-everything
```

## Usage

Once you've installed the package, you can use it in your JavaScript projects to fire confetti using images, gifs, and components.

```javascript
import confettiEverything from 'confetti-everything';

// Specify the container element where you want to trigger the confetti.
const container = document.getElementById('your-container');

// Specify the confetti content you want to use.
const confettiOptions = {
  type: 'image', // You can choose 'image', 'gif', or 'other'.
  content: 'path/to/your/content.png', // Replace with the path to your image, gif, or component.
};

// Fire the confetti!
confettiEverything(container, confettiOptions);
```

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

Feel free to contribute to this project by following our contribution guidelines.

## Issues

If you encounter any issues or have questions, please open an issue on our issue tracker.

🎉🎉🎉





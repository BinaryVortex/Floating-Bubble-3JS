# Floating Bubble 3JS

A mesmerizing 3D animation featuring a refractive sphere surrounded by floating bubbles, built with Three.js and GLSL shaders.

## Demo

View the live demo: [https://binaryvortex.github.io/Floating-Bubble-3JS/](https://binaryvortex.github.io/Floating-Bubble-3JS/)

![Screenshot](Screenshot%202025-11-09%20235741.png)

## Description

This project showcases a Fresnel refractive sphere in the center, with 20 smaller floating icosahedrons (bubbles) orbiting around it. The scene uses environment mapping for realistic reflections and refractions.

Inspired by the #CodepenChallenge - "Circle" theme.

## Features

- GLSL vertex and fragment shaders for advanced material effects
- Dynamic camera movement around the scene
- Environment cubemap for immersive background
- Animated floating bubbles with sinusoidal motion
- Responsive design that adapts to window resize

## Technologies Used

- Three.js - 3D graphics library
- GLSL - Shading language for custom materials
- HTML5 Canvas for rendering

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/BinaryVortex/Floating-Bubble-3JS.git
   ```
2. Open `index.html` in your web browser.

No additional setup required - all dependencies are loaded from CDNs.

## Browser Support

Requires WebGL support. Works in modern browsers like Chrome, Firefox, Safari, and Edge.

## Contributing

Feel free to fork and submit pull requests. Suggestions and improvements are welcome!

## License

This project is open source and available under the [MIT License](LICENSE).

## Credits

- HDRI environment map from CodePen assets
- Three.js library
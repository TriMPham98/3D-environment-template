# 3D Environment Template

This repository contains the starter files and instructions to create a 3D environment using Three.js and Vite.

## Setup Instructions

1. Clone this repository to your local machine.

2. Ensure you have Node.js and npm installed on your system.

3. Open a terminal and navigate to the cloned project's directory.

4. Run the following commands in order:

   ```
   npm install
   npm install three
   npm install gsap@3.5.1
   npm install vite --save-dev
   ```

   These commands will install the necessary dependencies, including Three.js, GSAP for animations, and Vite for development and building.

5. Create or update the following files in your project directory:

   - `index.html`: The main HTML file
   - `main.js`: The JavaScript file containing your Three.js scene
   - `styles.css`: CSS styles for your page
   - `vite.config.js`: Configuration file for Vite
   - `package.json`: Project configuration and dependencies

   (Refer to the project files for the content of these files)

## Running the Project

To preview the 3D environment:

1. Run the following command in your terminal:

   ```
   npm run dev
   ```

2. Open the URL provided by Vite in your web browser (usually `http://localhost:3000`).

## Initial Environment Demo

The initial setup creates a basic 3D scene with a rotating green cube. You can use this as a starting point to build more complex 3D environments.

## Customization

Feel free to modify the `main.js` file to add more 3D objects, lights, or interactions to your scene. You can also update the CSS in `styles.css` to change the appearance of your page.

## Building for Production

To create a production-ready build:

1. Run the following command:

   ```
   npm run build
   ```

2. The built files will be in the `dist` directory, ready for deployment.

## Additional Resources

- [Three.js Documentation](https://threejs.org/docs/)
- [Vite Documentation](https://vitejs.dev/guide/)
- [GSAP Documentation](https://greensock.com/docs/)

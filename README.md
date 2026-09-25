# Computer Graphics: Interactive 3D Object using JavaScript and GLSL (WebGL Environment)

This project demonstrates an **interactive 3D object** built using **JavaScript** and **GLSL** within a **WebGL environment**. The application provides users with controls to manipulate the object and its hierarchical components in real-time, showcasing the capabilities of WebGL for interactive 3D graphics in the browser.

## Features

### 3D Visualization
- A detailed 3D model of a vehicle with various components, including:
  - Chassis
  - Wheels
  - Rear spoiler
- Rendered using WebGL, leveraging GLSL shaders for lighting, materials, and transformations.

### User Interaction
- **Transformations**:
  - Move the parent object along the X, Y, and Z axes using sliders.
  - Control camera movement to adjust the view angle and zoom level.
- **Hierarchical Transformations**:
  - Apply transformations to specific parts of the model:
    - **Parent**
    - **Child**
    - **Grandchild**
  - Adjustable speed for grandchild transformations.
- **Reset Functionality**:
  - Reset rotations or other transformations to their default state.

### Real-Time Rendering
- Interactive inputs update the 3D scene dynamically.
- Smooth animations and responsive UI enhance the user experience.


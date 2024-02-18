# React Custom Select Component

## Features

- Multi-select and single-select functionality
- Keyboard navigation for accessibility
- Stylish and customizable with CSS Modules
- Lightweight and easy to integrate into React projects

## Usage

1. **Installation:**

    ```bash
    npm install
    ```

2. **Run the development server:**

    ```bash
    npm run dev
    ```

3. **Build for production:**

    ```bash
    npm run build
    ```

4. **Component Integration:**

   - Import the `Select` component into your project.
   - Use it in your React components with provided props for multi-select or single-select.

   ```jsx
   import { Select } from 'path/to/Select';

   function YourComponent() {
     // Your code here
     return (
       <Select
         options={[/* Your options here */]}
         // Other props based on your use case
       />
     );
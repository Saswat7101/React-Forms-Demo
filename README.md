# React Forms Demo

This project demonstrates building a React login form with custom validation logic, reusable components, and hooks. It showcases progressive enhancement of form handling from basic submission to advanced validation techniques.

## Project Setup

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd react-forms-demo
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

## Key Features

- **Progressive Validation**: Validation occurs on blur, submission, and real-time
- **Reusable Components**: Modular `Input` component for consistent UI
- **Custom Hooks**: `useInput` hook for state management and validation
- **Utility Functions**: Centralized validation logic in `validation.js`
- **Error Handling**: Clear error messages and visual feedback

## File Structure

```
src/
├── components/
│   ├── Input.jsx          # Reusable input component
│   ├── StateLogin.jsx     # Login form using state and hooks
│   └── ...
├── hooks/
│   └── useInput.js        # Custom hook for input management
├── util/
│   └── validation.js      # Validation utility functions
└── App.jsx                # Main application component
```

## Technologies Used

- React 18
- Vite (build tool)
- JavaScript (ES6+)
- CSS for styling

## Learning Objectives

This demo covers:

- React component composition
- Custom hooks creation and usage
- Form validation strategies
- State management in forms
- Progressive enhancement of user interfaces
- Code organization and reusability

## Next Steps

- Add more input types (checkbox, select, etc.)
- Implement form persistence (localStorage)
- Add server-side validation
- Integrate with a backend API
- Add unit tests for components and hooks

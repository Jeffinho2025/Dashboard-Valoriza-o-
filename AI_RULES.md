### Tech Stack

*   **React**: The core library for building interactive user interfaces.
*   **TypeScript**: Provides static type checking for improved code quality and maintainability.
*   **Tailwind CSS**: A utility-first CSS framework used for all styling, enabling rapid and consistent UI development.
*   **Recharts**: A declarative charting library built with React components, used for data visualization.
*   **Vite**: The build tool providing a fast development server and optimized production builds.
*   **Font Awesome**: Utilized for scalable vector icons throughout the application.
*   **Local Storage**: Used for client-side data persistence, such as saving SG (Segurança de Gols) data.
*   **CORS Proxy**: Employed to facilitate cross-origin API requests to external data sources.

### Library Usage Rules

*   **UI/Styling**: Always use **Tailwind CSS** for all styling. Prioritize utility classes for layout, spacing, colors, and other design aspects.
*   **Component Library**: For new UI components, leverage **shadcn/ui** components where applicable. If a specific component is not available or requires significant customization, create a new custom component in `src/components/`.
*   **Icons**: Use **Font Awesome** for all icons.
*   **Charting and Data Visualization**: Use **Recharts** for all charts and graphs.
*   **Routing**: Implement routing using **React Router**. All routes should be defined in `src/App.tsx`.
*   **API Calls**: Use the native **`fetch` API** for making HTTP requests.
*   **State Management**: Utilize **React's built-in hooks** (`useState`, `useContext`, `useReducer`) for state management. Avoid external state management libraries unless explicitly requested.
*   **File Structure**:
    *   Components should be placed in `src/components/`.
    *   Pages should be placed in `src/pages/`.
    *   Utility functions should be placed in `src/utils/`.
    *   New components should always be created in their own dedicated file.
*   **Responsiveness**: All designs must be responsive and adapt well to different screen sizes.
*   **Error Handling**: Do not use `try/catch` blocks for error handling unless specifically requested. Errors should be allowed to bubble up for centralized handling.
*   **Simplicity**: Prioritize simple and elegant solutions. Avoid over-engineering and focus on the minimum changes needed to fulfill the user's request.
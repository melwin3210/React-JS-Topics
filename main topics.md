

---

### 1. **Hooks**  
- **useState**: Manages local state in functional components.  
- **useEffect**: Executes side effects (e.g., fetching data, subscriptions).  
- **useContext**: Accesses context without prop drilling.  
- **useReducer**: Handles complex state logic with a reducer.  
- **useMemo**: Optimizes performance by memoizing expensive calculations.  
- **useCallback**: Memoizes functions to prevent unnecessary renders.  
- **useRef**: Stores mutable values and DOM references persistently.

---

### 2. **Higher Order Components (HOC)**  
- **What**: A function that takes a component and returns an enhanced one.  
- **When**: Reuse logic or modify behavior.  
- **Why**: Encourages reusability and clean separation of concerns.  
- **How**: Wrap components with additional logic (e.g., authentication, theming).

---

### 3. **Life Cycle Methods (Class Components)**  
- **Mounting**: `componentDidMount()` – DOM insertion logic.  
- **Updating**: `componentDidUpdate()` – Response to prop/state changes.  
- **Unmounting**: `componentWillUnmount()` – Cleanup operations.

---

### 4. **State Management**  
- **State vs Props**: Internal (state) vs external (props) data.  
- **Props Drilling**: Avoid deep prop passing with Context API.  
- **Context API**: Centralized state for global access without drilling.

---

### 5. **Redux/Zustand**  
- **Redux Workflow**: State → Actions → Reducers → Store.  
- **When**: Large applications with shared state.  
- **Why**: Centralized, predictable state management.  
- **Redux Toolkit (RTK)**: Simplifies Redux implementation.  
- **Zustand**: Lightweight state management alternative.

---

### 6. **Custom Hooks**  
- **When**: Reuse logic across components.  
- **Why**: Improves organization and readability.  
- **Structure**: Functions prefixed with `use`.

---

### 7. **Lazy Loading**  
- **Code Splitting**: Breaks app into smaller chunks.  
- **Suspense**: Handles loading states for lazy-loaded components.  
- **Why**: Reduces initial load time.

---

### 8. **Virtual DOM**  
- **Reconciliation**: Efficient diffing algorithm for updates.  
- **React Fiber**: Improves rendering performance.  
- **Diff Algorithm**: Compares old and new DOMs for changes.

---

### 9. **SSR vs CSR**  
- **SSR (Server-Side Rendering)**: Renders on the server; improves SEO and initial load.  
- **CSR (Client-Side Rendering)**: Renders on the client; better interactivity.  

---

### 10. **Routing (RBAC)**  
- **Protected Routes**: Use authentication checks for route access.  
- **react-router**: Popular library for declarative routing.  
- **Dynamic Routing**: Create routes dynamically based on data.

---

### 11. **Testing**  
- **React Testing Library**: Emphasizes testing behavior over implementation.  
- **Unit Testing**: Tests small, isolated units of functionality.

---

### 12. **Async Tasks**  
- **API Calls**: Fetch data using `fetch()` or `axios`.  
- **useEffect**: Manage async effects like data fetching.  
- **Promises**: Handle async operations with `.then()` and `.catch()`.  

---

### 13. **Best Practices**  
- **Reusability**: Modular components and hooks.  
- **Readability**: Clear naming conventions and documentation.  
- **Testability**: Write unit tests for reusable logic.

---

### 14. **Performance Optimization**  
- **Lazy Loading**: Load resources as needed.  
- **Asset Optimization**: Minify and compress assets.  
- **Bundlers**: Tools like Webpack or Vite for optimized builds.  
- **CDN**: Use content delivery networks for faster access.

---

### 15. **Styling**  
- Libraries: **Tailwind CSS**, **Bootstrap**, **Material UI**, **Ant Design**.  
- **CSS-in-JS**: Inline styles using libraries like **StyleX**.  
- **SCSS/CSS**: Traditional cascading styles.

---

# alx-project-0x08-setup
HookMastery: Unleashing the Power of Hooks
# alx-project-0x06-setup

This repository contains the implementation of a shared layout and related features using **Next.js**. It includes reusable components such as a Header, Footer, and Layout, as well as a button component and error handling with a custom 404 page. This project is designed to follow best practices and maintain a clean, organized structure.

## Features

1. **Shared Layout**  
   - Implementation of a common Header, Footer, and Layout to ensure DRY principles.
   - Components built with **TypeScript** and styled using **Tailwind CSS**.
   - `Button` component for reusable, styled buttons.

2. **Google Fonts Integration**  
   - Integrated Montserrat font for consistent typography across the application.

3. **Imperative Routing**  
   - Utilized `useRouter` from `next/router` for navigation to different features.

4. **Custom 404 Page**  
   - A user-friendly, humorous 404 page to handle unresolved routes.

5. **Interfaces Management**  
   - Centralized interface definitions under a dedicated directory for better organization and reusability.

## Implementation Details

### Shared Layout Components

#### 1. Header Component  
**File:** `components/layouts/Header.tsx`  
- Contains navigation links for easy app navigation.  
- Includes styled buttons (`Sign In`, `Sign Up`) for user actions.  
- Fully responsive and adheres to modern design standards.

#### 2. Footer Component  
**File:** `components/layouts/Footer.tsx`  
- Displays a brief description of the app or organization.  
- Includes links to useful resources and social media icons for easy accessibility.  

#### 3. Layout Component  
**File:** `components/layouts/Layout.tsx`  
- Combines the `Header`, `Footer`, and `children` content dynamically.  
- Acts as a wrapper for pages to maintain a consistent layout.

---

### Button Component  
**File:** `components/common/Button.tsx`  
- A reusable and customizable button component.  
- Supports the following props:
  - `label`: The text displayed on the button.
  - `size`: The size of the button (e.g., `small`, `medium`, `large`).
  - `color`: The button's background color.
  - `onClick`: A function to handle button click actions.

---

### Google Fonts  
**Integration:**  
- The **Montserrat** font is imported and applied globally in `styles/global.css`.  
- Ensures a professional and modern look across all pages.

---

### Imperative Routing  
**Implementation:**  
- Navigation is handled programmatically using `useRouter` from `next/router`.  
- Enables seamless routing between pages with JavaScript logic.  
- Example implementation can be found in `pages/index.tsx`.

---

### Custom 404 Page  
**File:** `pages/404.tsx`  
- Provides a user-friendly error page with a humorous touch.  
- Enhances the user experience by handling unresolved routes gracefully.

---

### Centralized Interfaces  
**File:** `interfaces/index.ts`  
- All TypeScript interfaces are organized in one directory.  
- Promotes reusability and maintains a clean project structure.

---

# Senior Frontend Engineer Technical Assessment - Saintly

## Overview
Build an MVP for SendCustomisedGift.com - a platform where users can find products and customize them with engravings or printed text.

## Time Limit
- 2-4 hours maximum
- If you run out of time, document your TODOs and explain your next steps

## Task Requirements

### 1. UI Component Library
Create the following reusable components:
- Card: Display product information with consistent styling
- Text Input: Reusable input field with proper validation states
- Select Input: Dropdown component with options handling
- Button: Versatile button component with different variants

### 2. Layout Implementation
Create a responsive layout with:
```
DESKTOP:
+----------------------------------------+
|              TopNavBar                 |
|   [Logo]  [Search]  [User Menu]       |
+-------------+--------------------------+
| LeftNavBar  | Content                 |
| [Home]      | +--------------------+  |
| [Products]  | | Dynamic Content    |  |
| [Categories]| | (Products Grid)    |  |
| [Settings]  | +--------------------+  |
+-------------+--------------------------+

MOBILE:
+----------------------------------------+
|              TopNavBar                 |
| [☰] [Logo]              [User Menu]   |
+----------------------------------------+
|           Dynamic Content              |
|         (Products Grid)               |
+----------------------------------------+
```

### 3. Products Page Features
- Responsive product grid
  - Mobile: 1 card per row
  - Desktop: Dynamic grid (min-width: 200px, max-width: 300px)
- Search functionality
- Bonus: Category filtering (dropdown)
- Product cards with:
  - Product image
  - Title
  - Price
  - "Learn More" link

### 4. Product Detail Page
- SEO optimization
- Responsive design
- Product information display
- Buy Now functionality

## Technical Requirements

### Next.js Features
Demonstrate understanding of:
- Server vs Client Components
- Shared Layout implementation (create your own layout.tsx)
- Metadata configuration
- Route Handlers
- Middleware usage
- Data Caching strategies
- Page Rendering Strategies (SSR vs CSR vs ISR)
- Error Boundaries

### Performance Considerations
- Implement appropriate caching strategies
- Choose correct rendering method per page/component
- Optimize images and assets
- Implement loading states

## Getting Started

1. Install dependencies:
```bash
npm install
```

2. Run the development server:
```bash
npm run dev
```

3. Open [http://localhost:3000](http://localhost:3000)


## Evaluation Criteria

### Code Quality
- Clean, maintainable code
- TypeScript usage
- Component organization
- Code reusability
- Proper error handling

### Functionality
- All features working as expected
- Responsive design
- Navigation works correctly
- Search and filtering work properly

### Performance
- Appropriate caching implementation
- Correct rendering strategy choices
- Loading states
- Image optimization

### UI/UX
- Clean, modern design
- Intuitive user interactions
- Responsive behavior
- Loading states and error handling

## Submission
- Ensure all code is committed
- Include a TODO.md if you ran out of time
- Document any assumptions or decisions made

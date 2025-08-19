# React Component Development Assignment

## 🎯 Overview
Build two production-ready React components using TypeScript, TailwindCSS, and Storybook. This assignment focuses on creating reusable, accessible, and well-documented UI components.

## 🚀 Quick Start

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Start Storybook
npm run storybook

# Build for production
npm run build
```
## 📖 Storybook Preview
You can view the live Storybook here: https://68a3997f09919dc38b9f20c3-fflnekmzjw.chromatic.com/

## 📋 Assignment Requirements

### Component 1: InputField
A flexible input component with comprehensive validation and styling options.

**Features to implement:**
- Text input with label, placeholder, helper text, error message
- States: disabled, invalid, loading
- Variants: filled, outlined, ghost
- Sizes: small, medium, large
- Optional: clear button, password toggle
- Optional: Support for light & dark theme

### Component 2: DataTable
A data table component with sorting and selection capabilities.

**Features to implement:**
- Display tabular data
- Column sorting
- Row selection (single/multiple)
- Loading state
- Empty state

## 📁 Project Structure

```
src/
├── components/
│   ├── InputField/
│   │   ├── InputField.tsx
│   │   ├── InputField.stories.tsx
│   │   └── InputField.test.tsx
│   └── DataTable/
│       ├── DataTable.tsx
│       ├── DataTable.stories.tsx
│       └── DataTable.test.tsx
├── types/
├── utils/
└── styles/
```

## 🧪 Testing
Run component tests:
```bash
npm run test
```

## 📚 Documentation
All components are documented in Storybook with interactive examples and usage guidelines.


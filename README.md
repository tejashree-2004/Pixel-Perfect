# Knowledge Quiz — Frontend Intern Assignment

A pixel-perfect, production-quality implementation of an interactive quiz application built with React, TypeScript, and Tailwind CSS.

## 🎯 Project Overview

This project demonstrates frontend engineering excellence through a beautifully crafted quiz interface that prioritizes:

- **Pixel-Perfect Design**: Faithful recreation of the Figma mockups with attention to every detail
- **Premium Animations**: Smooth micro-interactions using Framer Motion
- **Accessibility First**: WCAG 2.1 compliant with full keyboard navigation
- **Clean Architecture**: Modular, reusable component structure

## 🏗️ Architecture

## 🎨 Design System

The project implements a complete design system including:

### Color Tokens
- **Primary**: Deep teal (#1a4a5c) - Used for headings and accents
- **Secondary**: Soft cyan - Answer cards and subtle backgrounds
- **Background**: Cosmic navy with star particles

### Typography
- **Display**: Playfair Display (serif, italic) - Headlines
- **Body**: Inter (sans-serif) - Body text and UI

### Spacing & Shadows
- Consistent 8px grid system
- Layered shadow system for depth

## ♿ Accessibility Features

- **Keyboard Navigation**: Full tab support with visible focus states
- **Screen Reader Support**: Semantic HTML, ARIA labels, and live regions
- **Color Contrast**: All text meets WCAG AA standards
- **Skip Links**: Skip to main content functionality
- **Motion Preferences**: Respects `prefers-reduced-motion`

## 🚀 Technical Highlights

### Animations
- Framer Motion for declarative animations
- Staggered enter animations for options
- Spring physics for natural movement
- AnimatePresence for smooth page transitions

### State Management
- Custom `useQuiz` hook for quiz logic
- Memoized calculations for performance
- Type-safe with full TypeScript coverage

### Performance
- Tree-shakeable icon imports
- Optimized re-renders with proper memoization
- CSS custom properties for theming

## 🛠️ Tech Stack

- **Framework**: React 18 + TypeScript
- **Styling**: Tailwind CSS + CSS Custom Properties
- **Animations**: Framer Motion
- **Build Tool**: Vite
- **Icons**: Lucide React

## 📋 Engineering Decisions

1. **Custom Hook Pattern**: Separated quiz logic into `useQuiz` for testability and reusability

2. **Design Tokens**: All colors defined as CSS variables enabling future theming

3. **Component Composition**: Small, focused components that compose into features

4. **Accessibility by Default**: Every interactive element has keyboard support and ARIA attributes

5. **Animation Strategy**: Animations enhance UX without blocking interactions

## 🎯 Future Enhancements

- Timer functionality per question
- Multiple quiz categories
- Score persistence with localStorage
- Shareable results

---

*Built with ❤️ as a Frontend Intern Assignment demonstration*

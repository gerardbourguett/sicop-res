# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Development Commands

- `pnpm dev` - Start development server with HMR
- `pnpm build` - Build for production (runs TypeScript check + Vite build)
- `pnpm lint` - Run ESLint
- `pnpm preview` - Preview production build locally

## Technology Stack

- **React 19** with TypeScript
- **Vite** (using rolldown-vite experimental fork for faster builds)
- **ESLint** with TypeScript, React Hooks, and React Refresh rules
- **pnpm** as package manager

## Architecture

This is a standard Vite + React + TypeScript frontend application with:

- **Entry point**: `src/main.tsx` - renders the root App component
- **Main component**: `src/App.tsx` - currently a basic counter demo
- **Styling**: CSS modules with `src/App.css` and `src/index.css`
- **Assets**: Stored in `src/assets/` and `public/`

## Configuration Notes

- Uses `rolldown-vite@7.2.2` instead of standard Vite for performance
- TypeScript configuration split across `tsconfig.app.json` and `tsconfig.node.json`
- ESLint configured with recommended rules for TypeScript and React
- No test framework currently configured

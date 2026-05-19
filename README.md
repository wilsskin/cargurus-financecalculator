# CarGurus Finance Calculator
A mobile-first finance calculator for car buyers to estimate monthly payments and total cost.

[wilsskin.github.io/cargurus-financecalculator](https://wilsskin.github.io/cargurus-financecalculator)

---

## What It Does
- Supports dealer financing, outside loan, and cash payment types
- Auto-suggests APR from credit score; accepts loan term, down payment, and trade-in inputs
- Outputs estimated monthly payment and total cost in a persistent summary banner
- Lets users save or share their results

## How It's Built
React and TypeScript app built with Vite. Global state is managed via React Context and useReducer — user inputs dispatch to reducers, which trigger a recalculation of monthly payment and total cost on every change. UI components use shadcn/ui on Radix primitives, styled with Tailwind and CarGurus-aligned design tokens. Deployed via GitHub Pages.

**Stack:** React, TypeScript, Tailwind CSS, shadcn/ui, Vite, GitHub Pages

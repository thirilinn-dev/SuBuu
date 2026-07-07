# SuBuu - Smart Savings Tracker

SuBuu is a modern, responsive web application for tracking savings and transactions locally.

## Features

- **Left Navigation Sidebar**: Desktop view includes a persistent left navigation sidebar containing branding, active pages, dynamic savings goal calculations, theme controls, and owner profile metadata.
- **Responsive Drawer Menu**: Mobile views collapse the navigation sidebar into a smooth slide-out overlay drawer, triggered by a hamburger button.
- **Typography Scaling**: Clear visual hierarchy with scaled-up font sizes, ensuring high readability across desktop and mobile screens.
- **Dynamic Savings Goal**: Set custom goal targets (saved in localStorage) to track progress via an animated progress bar based on your current balance.
- **Theme Toggle Switch**: Seamless switching between light and dark modes.
- **Local Database**: All transactions (Deposits & Withdrawals) are stored locally in the browser using IndexedDB.

## Running Locally

To run the application, simply open `index.html` in any web browser, or serve it using a local HTTP server of your choice:

```bash
npx http-server .
```
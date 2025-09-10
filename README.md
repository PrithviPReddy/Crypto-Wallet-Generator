1. `npm create vite@latest`
2. `npm install`
3. `npm install vite-plugin-node-polyfills`
4. put this in your main.jsx
  ` import { StrictMode } from 'react'
import { createRoot } from 'react-dom/client'
import App from './App.jsx'
import './index.css'

createRoot(document.getElementById('root')).render(
  <StrictMode>
    <App />
  </StrictMode>,
)`

5. `npm install bip39 `

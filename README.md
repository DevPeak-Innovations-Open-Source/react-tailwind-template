# Install tailwindcss in react vite
- npm install tailwindcss @tailwindcss/vite

## Copy this to vite.config.js
```
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'
import tailwindcss from '@tailwindcss/vite'

export default defineConfig({
  plugins: [
    react(),
    tailwindcss(),
  ],
})
```

## Copy this in index.css
### Note:- this @import will not work in index.scss
```
@import "tailwindcss";

```

### Tailwind installed successfully!


### Frontend

| ------- | ------------| -------|
| ------- |:--------------:|:--------: |
| name    |   review-app   | ✅|
| version |     0.1.0      | ✅ |
| private |      true      |  ✅|

**scripts**
- "dev": "concurrently \"yarn run codegen\" next dev",   ✅
-  "build": "next build",  ✅
-  "start": "next start",    ✅
-   "lint": "next lint",       ✅
-  "codegen": "graphql-codegen --config codegen.ts --watch"

**dependencies**
-  "@hookform/resolvers": "^3.2.0",
- "@radix-ui/react-accordion": "^1.1.2",
- "@radix-ui/react-checkbox": "^1.0.4",
- "@radix-ui/react-dialog": "^1.0.4",
- "@radix-ui/react-dropdown-menu": "^2.0.5",
- "@radix-ui/react-icons": "^1.3.0",
- "@radix-ui/react-label": "^2.0.2",
- "@radix-ui/react-popover": "^1.0.6",
- "@radix-ui/react-slot": "^1.0.2",
- "@radix-ui/react-switch": "^1.0.3",
- "@radix-ui/react-tabs": "^1.0.4",
- "@radix-ui/react-tooltip": "^1.0.6",
- "@tanstack/react-query": "^4.32.6",
-  "@tanstack/react-query-devtools": "^4.32.6",
-  "@types/node": "20.4.9",
-  "@types/react": "18.2.19",
-  "@types/react-dom": "18.2.7",
-  "autoprefixer": "10.4.14",
-   "axios": "^1.4.0",
-   "class-variance-authority": "^0.7.0",
-   "clsx": "^2.0.0",
 -   "cmdk": "^0.2.0",
 -  "date-fns": "^2.30.0",
- "eslint": "8.46.0",
 - "eslint-config-next": "13.4.13",
    -"graphql": "^16.8.0",
    "graphql-request": "^6.1.0",
    "lucide-react": "0.263.1",
    "next": "13.4.13",
    "next-themes": "^0.2.1",
    "postcss": "8.4.27",
    "react": "18.2.0",
    "react-colorful": "^5.6.1",
    "react-device-frameset": "^1.3.4",
    "react-dom": "18.2.0",
    "react-hook-form": "^7.45.4",
    "react-hot-toast": "^2.4.1",
    "slugify": "^1.6.6",
    "tailwind-merge": "^1.14.0",
    "tailwindcss": "3.3.3",
    "tailwindcss-animate": "^1.0.6",
    "typescript": "^5.1.6",
    "uploadthing": "^5.6.1",
    "zod": "^3.22.0",
    "zustand": "^4.4.1"


**devDependencies** 
- "@graphql-codegen/cli": "5.0.0",
-  "@graphql-codegen/client-preset": "4.1.0",
-  "@graphql-codegen/introspection": "4.0.0",
-  "concurrently": "^8.2.0",
-  "prettier": "^3.0.3",
-  "prettier-plugin-tailwindcss": "^0.5.3"
  
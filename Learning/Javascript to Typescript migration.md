Step 1. Create separate boilerplate project with Vite, choosing TypeScript as the language variant.
Step 2. From that project, bring in all the config files that Vite provides: tsconfig.json and vite-env.d.ts
Step 3. Install all the TypeScript-related dependencies
Step 4. Add the TypeScript compiler to your build script by "build: "tsc && vite build"
Step 5. Rename each file you want to migrate to TypeScript and add te types as needed.
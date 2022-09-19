# We add this script in Head
```bash
<script src="https://cdn.tailwindcss.com"></script>
```
For installing Tailwindcss with server
```
npm init -y
```
```
npm install -D tailwindcss postcss autoprefixer vite
```
```
npx tailwindcss init -p
```
Aad This script in package.json file
```
"start": "vite"
"build": "vite build"
```
For starting server
```
npm run start
```
Build Css For Production (Deployment)
```
npm run build:tailwind
```
You can see the TailwindCss full file and customize the config file 
```
npx tailwindcss init NAME --full
```

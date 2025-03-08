# 1️⃣ Initialize Project
npm init -y  

# 2️⃣ Install Dependencies
npm install -D 

// tailwindcss postcss autoprefixer vite  

## npm install -D tailwindcss postcss autoprefixer
node modules 

# 3️⃣ Generate Tailwind Config
npx tailwindcss init -p  

# 4️⃣ Update tailwind.config.js  
echo 'export default { content: ["./index.html", "./src/**/*.{js,ts,jsx,tsx}"], theme: { extend: {} }, plugins: [] };' > tailwind.config.js  

# 5️⃣ Create Tailwind CSS File  
mkdir src && echo '@tailwind base;\n@tailwind components;\n@tailwind utilities;' > src/index.css  

# 6️⃣ Import CSS in main.js  
echo "import './index.css';" > src/main.js  

# 7️⃣ Start Vite Server  
npm run dev  

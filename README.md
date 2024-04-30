## Crear una app con next.js

npx create-next-app@latest --typescript --use-npm

Para que quede como en el proyecto de Jonathan Would you like to use ESLint with this project? › No / ++Yes++ Would you like to use src/ directory with this project? › ++No++ / Yes Would you like to use experimental app/ directory with this project? › ++No++ / Yes

## Ejecutar el proyecto

npm run dev

###  tsconfig.ts

“strict" : true 
"noImplicitAny": true,
 “noImplicitReturns”: true,

## Tailwind

npm install -D tailwindcss postcss autoprefixer npx tailwindcss init -p

tailwind.config.js

content: [ "./app//*.{js,ts,jsx,tsx}", "./pages//.{js,ts,jsx,tsx}", "./components/**/.{js,ts,jsx,tsx}", ],

## global.css

@tailwind base; @tailwind components; @tailwind utilities;


<!-- 

// Uso 
 <h1 className=“text-3xl font-bold underline”> Hello world! </h2> -->
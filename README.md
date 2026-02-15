\# Create react native project

```

npx create-expo-app my-app

```



\# Config tailwind (naitivewind)

```

npm install nativewind

npm install --save-dev tailwindcss

npx tailwindcss init



add tailwind.config.js



/\*\* @type {import('tailwindcss').Config} \*/

module.exports = {

&nbsp; content: \[

&nbsp;   "./App.{js,jsx,ts,tsx}",

&nbsp;   "./src/\*\*/\*.{js,jsx,ts,tsx}",

&nbsp; ],

&nbsp; theme: {

&nbsp;   extend: {},

&nbsp; },

&nbsp; plugins: \[],

}





add babel.config.js



module.exports = {

&nbsp; presets: \['babel-preset-expo'], // або 'module:metro-react-native-babel-preset' для CLI

&nbsp; plugins: \['nativewind/babel'],

};





```


    ### Projeto App Humburger
    * HTML5
    * CSS3
    * Javascript

#### Crinado Projeto
* 1. npm init -y
* 2. npm install -D tailwindcss
* 3. npx tailwindcss init

* 4. configurar o arquivo tailwind.config.js
```
/** @type {import('tailwindcss').Config} */
module.exports = {
  content: ["./**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}
```

* 5. configurar o arquivo style.css
```
@tailwind base;
@tailwind components;
@tailwind utilities;
```

* 6. package.json
```
    "dev": "npx tailwindcss -i ./styles.css -o ./styleOut.css --watch"
```
    * Link Ref :: 
    ```
    https://www.youtube.com/watch?v=rjXXDv23-6Y
    ```

    * Link Ref :: Parte 2
    ```
    https://www.youtube.com/watch?v=FXm7Dfre60I
    ```

    * Link Ref :: MENU LATERAL responsivo (SIDEBAR) 
    ```
    https://www.youtube.com/watch?v=lZVQGjTEX-w&t=70s
    ```

    * Link Ref :: Sidebar Menu with Animated Dropdowns 
    ```
    https://www.youtube.com/watch?v=R7b3OlEyqug
    ```
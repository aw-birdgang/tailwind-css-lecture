
# 
```bash

https://tailwindcss.com/docs/installation

# Install Tailwind CSS
npm install -D tailwindcss
npx tailwindcss init

# Configure your template paths
module.exports = {
  content: ["./src/**/*.{html,js}"],
  theme: {
    extend: {},
  },
  plugins: [],
}

# Add the Tailwind directives to your CSS
@tailwind base;
@tailwind components;
@tailwind utilities;

# Start the Tailwind CLI build process
npx tailwindcss -i ./input.css -o ./css/style.css --watch

```


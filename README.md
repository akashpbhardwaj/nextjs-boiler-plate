# Next.js Boilerplate

This is a boilerplate for building applications using Next.js and Tailwind CSS.

## Getting Started

### Prerequisites

- Node.js and npm

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/akashpbhardwaj/nextjs-boiler-plate.git
   cd nextjs-boilerplate
   ```

2. Install the dependencies:

   ```sh
   npm install
   ```

### Running the Application

1. Start the development server:

   ```sh
   npm run dev
   ```

2. Build the application for production:

   ```sh
   npm run build
   ```

3. Start the production server:

   ```sh
   npm start
   ```

### Project Structure

```sh
nextjs-boilerplate
├── public
├── src
│   ├── components
│   ├── config
│   ├── hooks
│   ├── lib
│   ├── pages
│   │   ├── api
│   │   ├── _app.js
│   │   ├── _document.js
│   │   └── index.js
│   ├── store
│   ├── styles
│   │   └── globals.css
│   └── utils
├── .gitignore
├── package.json
├── tailwind.config.js
├── postcss.config.js
└── README.md
```

### Customization

1. Update the `tailwind.config.js` file to customize Tailwind CSS.

### Adding New Pages

Create a new file in the `src/pages` directory. For example, to add a new page `about`, create `src/pages/about.js`:

```js
export default function AboutPage() {
  return (
    <div>
      <h1>About Page</h1>
      <p>This is the about page.</p>
    </div>
  );
}
```

### License

This project is licensed under the MIT License.

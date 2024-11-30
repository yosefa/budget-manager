### init tailwind
```
npm init -y
npm install tailwindcss postcss autoprefixer
npx tailwindcss init
```

### update tailwind.config.js
```
...
content: ['./index.html'],
...
```

### generate css
```
npx tailwindcss build -o tailwind.css --watch
```

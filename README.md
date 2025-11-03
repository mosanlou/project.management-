# Project Management App

A React-based project management application that helps you organize and track your projects and tasks efficiently.

## 🚀 Live Demo
Check out the live application: [Project Management App](https://mosanlou.github.io/project.management-/)

## ✨ Features

- Create and manage multiple projects
- Add tasks to each project
- Track project deadlines
- Modal-based form validation
- Responsive design with Tailwind CSS
- Modern React practices (Hooks, Refs)

## 🛠️ Built With

- React
- Vite
- Tailwind CSS
- GitHub Pages

## 🏗️ Installation

1. Clone the repository:
```bash
git clone https://github.com/mosanlou/project.management-.git
cd project.management-
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## 📦 Deployment

### Manual Deployment
To deploy updates to GitHub Pages:

```bash
# Commit your changes
git add .
git commit -m "your commit message"
git push

# Deploy to GitHub Pages
npm run deploy
```

The site will be automatically built and deployed to: https://mosanlou.github.io/project.management-/

### Automatic Deployment
The project is configured with GitHub Actions for automatic deployment. Any push to the `main` branch will trigger a deployment to GitHub Pages.

## 🔧 Development

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run deploy` - Deploy to GitHub Pages

## 📁 Project Structure

```
project.management-/
├── src/
│   ├── Components/
│   │   ├── Button.jsx
│   │   ├── Input.jsx
│   │   ├── Modal.jsx
│   │   ├── NewProject.jsx
│   │   ├── NewTask.jsx
│   │   ├── ProjectsSidebar.jsx
│   │   ├── SelectedProject.jsx
│   │   └── Tasks.jsx
│   ├── App.jsx
│   └── main.jsx
├── public/
├── index.html
└── package.json
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).
# 📰 News App v2

A modern, responsive News Application built with **React**, **TypeScript**, and **Vite** that fetches and displays real-time headlines using **NewsAPI.org**. 

---

## ✨ Features

* 🌍 **Real-time News**: Fetches the latest headlines dynamically.
* 🗂️ **Category Filtering**: Filter news by categories like Technology, Sports, Politics, and more.
* ⚡ **Optimized Data Fetching**: Utilizes **TanStack React Query** for efficient caching, background updates, and state management.
* 🎨 **Modern UI**: Designed with **Tailwind CSS v4** for a clean, responsive, and beautiful interface.
* 🔗 **External Links**: Seamlessly read full articles by opening them in new tabs.
* 📱 **Fully Responsive**: Optimized for desktops, tablets, and mobile devices.

---

## 🛠️ Tech Stack

* **Frontend**: React 19, TypeScript, Vite
* **Styling**: Tailwind CSS v4, Lucide React (Icons)
* **Data Fetching & State**: Axios, TanStack React Query
* **Linting & Formatting**: ESLint

---

## 📂 Project Structure

```
news-app/
│
├── public/               # Static assets
├── src/
│   ├── components/       # Reusable UI components (NewsCards, Filters, etc.)
│   ├── hooks/            # Custom React hooks (e.g., API fetching hooks)
│   ├── services/         # API configuration and Axios instances
│   ├── types/            # TypeScript interfaces and types
│   ├── App.tsx           # Main application component
│   └── main.tsx          # Application entry point
│
├── index.html
├── package.json
├── tsconfig.json
└── vite.config.ts
```

---

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/akashb8/News-App-V2.git
   cd news-app
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Environment Variables:**
   Create a `.env` file in the root directory and add your NewsAPI key:
   ```env
   VITE_NEWS_API_KEY=your_api_key_here
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

---

## 🚀 Build for Production

To create a production-ready build:

```bash
npm run build
```

To preview the production build locally:

```bash
npm run preview
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to fork the repository and submit a pull request.

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 👨‍💻 Author

**Akash Bhattacharyya**  
[GitHub Profile](https://github.com/akashb8)

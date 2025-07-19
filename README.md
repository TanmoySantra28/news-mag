# 📰 NewsNow - React News Aggregator

**NewsNow** is a responsive and modern news application built using **React JS** and **Vite**. It fetches the latest headlines from the [News API](https://newsapi.org) and displays them beautifully in card layouts. Users can filter news by categories like **Technology**, **Business**, **Health**, **Sports**, and **Entertainment**.

## 🚀 Features

- 📡 Fetches live news using News API
- 📂 Category filtering (Technology, Business, Health, Sports, Entertainment)
- 📰 Clean and modern card layout for news items
- 🧭 Sticky navigation bar
- ⚡ Built with React + Vite for fast performance
- 📱 Responsive design for all screen sizes
- 👆 Clicking on the news cards will redirect you to the detailed sites.

## 📸 Preview

#### Default News feed
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/e08267ed-2c9f-4b66-93a4-12ea2b6074d6" />

#### Technology News feed
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/dc972435-88cb-4e2e-aec3-af5722ca487a" />

## 🛠️ Tech Stack

- **React JS** (Component-based architecture)
- **Vite** (Fast bundler and development server)
- **JavaScript (ES6+)**
- **CSS Modules**

## 📁 Project Structure

```
NEWS-MAG/
├── public/
├── src/
│ ├── assets/
│ │ └── bpa9gz6v.png
│ ├── Components/
│ │ ├── Navbar.jsx
│ │ ├── NewsBoard.jsx
│ │ └── NewsItem.jsx
│ ├── App.jsx
│ ├── App.css
│ ├── index.css
│ └── main.jsx
├── .env
├── .gitignore
├── .gitattributes
├── .eslint.config.js
├── LICENSE
├── index.html
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```


## 🔧 Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/TanmoySantra28/news-mag.git
cd news-mag
```
### 2. Install dependencies
```
npm install
```
### 3. Configure your API Key
- Sign up at https://newsapi.org
- Create a .env file in the root directory and add:
```
VITE_NEWS_API_KEY=your_api_key_here
```
### 4. Run the development server
```
npm run dev
```
- The app will be running at http://localhost:5173

## ✨ Customization

You can easily customize the categories or layout by modifying:

- Navbar.jsx – to add/remove categories
- NewsBoard.jsx – to fetch and filter news articles
- App.css – for styling the UI

## 📄 License

This project is open-source and free to use under the MIT License.

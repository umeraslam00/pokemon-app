# Pokémon Explorer App

A simple and interactive Pokémon browser built with **React Native** and **Expo Router**, powered by the **PokeAPI**.
Users can explore Pokémon, view their types, images, abilities, and detailed stats.

---

## 🚀 Features

* 📜 Browse a list of Pokémon (first 20)
* 🎨 Dynamic background colors based on Pokémon type
* 🔗 Navigation using Expo Router
* 🖼️ Front and back sprite display
* 📊 Detailed Pokémon stats (HP, Attack, etc.)
* ⚡ Ability listing
* 📏 Height, weight, and base experience
* 🧠 Clean and beginner-friendly code structure

---

## 🛠️ Tech Stack

* **React Native**
* **Expo**
* **Expo Router**
* **TypeScript**
* **PokeAPI**

---

## 📂 Project Structure

```
/app
  ├── index.tsx        # Home screen (Pokémon list)
  ├── details.tsx      # Pokémon details screen
/global.css            # Tailwind / global styles
```

---

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/your-username/pokemon-explorer.git
cd pokemon-explorer
```

### 2. Install dependencies

```bash
npm install
```

### 3. Start the app

```bash
npx expo start
```

---

## 📡 API Used

This project uses the free public API:

👉 https://pokeapi.co/

---

## 🧩 How It Works

### Home Screen (`index.tsx`)

* Fetches a list of Pokémon
* Makes additional API calls to get detailed data
* Displays:

  * Name
  * Type
  * Front & Back images
* Navigates to details screen on click

---

### Details Screen (`details.tsx`)

* Fetches data using Pokémon name
* Displays:

  * Official artwork
  * Types (with colored badges)
  * Height, weight, experience
  * Abilities
  * Stats with progress bars

---

## 🎨 UI Highlights

* Dynamic type-based colors
* Scrollable layout
* Responsive design
* Simple and clean UI

---

## 📌 Future Improvements

* 🔍 Search Pokémon
* 📄 Pagination / Infinite scroll
* ❤️ Favorites system
* 🌙 Dark mode
* ⚔️ Pokémon comparison feature
* 🎮 Add animations

---

## 🐛 Known Issues

* Limited type color mapping (only a few types handled)
* No loading spinner (only text)
* No error UI handling

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make changes
4. Submit a pull request

---

## 📄 License

This project is open-source and available under the MIT License.

---

## 🙌 Acknowledgements

* Thanks to **PokeAPI** for providing free Pokémon data
* Expo team for amazing developer tools

---

## 👨‍💻 Author

Your Name
GitHub: https://github.com/umeraslam00
website: https://umeraslam.com

---

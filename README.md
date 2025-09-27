
# VibeFinder 🎶 – Music Discovery & Visualization Tool

![VibeFinder Banner](https://user-images.githubusercontent.com/your-image-link/banner-placeholder.png)

**VibeFinder** is an interactive web application that allows users to explore music data directly from **Spotify**. It combines **Spotify API integration**, **data visualization**, and a **user-friendly interface** to provide an engaging way to discover songs, albums, and trends in music over time.



## 🔹 Features

1. **Song List**

   * Displays a comprehensive list of songs fetched from Spotify.
   * Includes song names, artists, album titles, and release dates.

2. **Albums by Year (Bar Chart 📊)**

   * Visualizes the number of albums released each year using an interactive bar chart.
   * Helps users analyze music trends over time.

3. **Search Functionality 🔍**

   * Search for songs, artists, or albums instantly.
   * Real-time suggestions improve discoverability.

4. **Responsive Design 📱**

   * Works smoothly on desktops, tablets, and mobile devices.
   * Modern and intuitive layout for easy navigation.

5. **Real-Time Data**

   * All information is dynamically fetched from the **Spotify API**, ensuring up-to-date results.

---

## 🔹 Technology Stack

| Layer              | Technology / Library         |
| ------------------ | ---------------------------- |
| Frontend           | React, HTML, CSS, JavaScript |
| Data Visualization | Chart.js / Recharts          |
| API Integration    | Spotify Web API              |
| Styling            | CSS3, Responsive Design      |
| Package Management | npm / yarn                   |

---

## 🔹 Installation

1. **Clone the repository**

```bash
git clone https://github.com/Safa-khanum/VibeFinder-Music-Tool.git
cd VibeFinder-Music-Tool
```

2. **Install dependencies**

```bash
npm install
```

3. **Set up Spotify API credentials**

* Go to [Spotify Developer Dashboard](https://developer.spotify.com/dashboard/).
* Create an app to get your `Client ID` and `Client Secret`.
* Add these credentials in your `.env` file (example below):

```env
REACT_APP_SPOTIFY_CLIENT_ID=your_client_id
REACT_APP_SPOTIFY_CLIENT_SECRET=your_client_secret
```

4. **Start the development server**

```bash
npm start
```

* Open your browser at `http://localhost:3000` to see the app in action.

---

## 🔹 Usage

* **Browse Songs:** View all songs in the main list.
* **Filter by Artist/Album:** Use the search bar to filter songs by artist or album.
* **View Album Trends:** See the bar chart showing how many albums were released each year.

---

## 🔹 Screenshots

**Song List:**
![Song List Screenshot](https://user-images.githubusercontent.com/your-image-link/song-list-placeholder.png)

**Albums by Year Chart:**
![Albums Chart Screenshot](https://user-images.githubusercontent.com/your-image-link/chart-placeholder.png)

---

## 🔹 Future Enhancements

* User authentication to save favorite songs and playlists.
* More visualizations like genre-based charts or popularity trends.
* Dark/light mode toggle for better user experience.
* Integration with Spotify playback API to play songs directly.

---

## 🔹 Contribution

Contributions are welcome! 🎉

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature`
3. Commit your changes: `git commit -m "Add your feature"`
4. Push to the branch: `git push origin feature/your-feature`
5. Open a Pull Request

---

## 🔹 License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

---

## 🔹 Contact

* **Developer:** Safa Khanum
* **GitHub:** [Safa-khanum](https://github.com/Safa-khanum)
























# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

# AquaTrack - Smart Water Consumption Tracker

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)

**AquaTrack** is a beautiful, interactive web application that helps you monitor your daily water intake, set hydration goals, and visualize your consumption patterns. Stay healthy and mindful about your hydration habits with an intuitive dashboard, real-time statistics, and persistent local storage.

🔗 **Live Demo:** [AquaTrack Demo](#) *(replace with your GitHub Pages link)*

![AquaTrack Screenshot](https://via.placeholder.com/800x450?text=AquaTrack+Dashboard+Preview)  
*(Add a real screenshot of your app here)*

## Features

- ** Log Water Intake** – Add your daily water consumption in liters with a specific date.
- ** Quick Add Presets** – One‑click logging for common amounts (glass, bottle, 1L, 1.5L).
- ** Personalized Daily Goal** – Set and update your own hydration target (default 2.7L).
- ** Weekly Overview Chart** – Beautiful bar chart showing your last 7 days of water intake using Chart.js.
- ** Recent Entries List** – View and delete individual logs with an intuitive interface.
- ** Live Statistics** – See today’s total, weekly average, and goal completion percentage at a glance.
- ** Persistent Storage** – All data is saved in your browser’s `localStorage` – no backend required.
- ** Fully Responsive** – Works seamlessly on desktop, tablet, and mobile devices.
- ** Modern UI** – Clean gradient design, smooth animations, and water‑inspired color palette.

## How to Use

1. **Add a new entry**  
   - Enter the amount (in liters) and select a date.  
   - Or use the **Quick Add** dropdown for common serving sizes.  
   - Click **Add** or **Quick +** to save.

2. **Set your daily goal**  
   - Adjust the number in the **Daily target** field and click **Set**.  
   - The circular progress indicator will update in real time.

3. **Manage your history**  
   - View all recent entries in the **Recent logs** panel.  
   - Delete individual entries with the trash icon.  
   - Use **Reset today** to clear all entries for the current day.  
   - **Clear all** removes your entire water history.

4. **Track your progress**  
   - The weekly bar chart gives you a clear overview of your habits.  
   - Top statistic cards show today’s total, your goal, and the weekly average.

## 🛠️ Tech Stack

- **HTML5** – Semantic structure
- **CSS3** – Flexbox, Grid, gradients, and responsive design
- **JavaScript (ES6)** – Core logic, localStorage API, DOM manipulation
- **Chart.js** – Interactive and customizable weekly bar chart
- **Font Awesome** – Icon library for visual enhancement
- **Google Fonts** – Inter typeface for modern typography

## Project Structure

```
water-consumption-tracker/
├── index.html          # Main application (self-contained)
├── README.md           # Project documentation
└── screenshot.png      # (Optional) App preview image
```

> **Note:** The entire application is contained in a single HTML file, making it easy to deploy or customize.

## Installation & Local Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/aquatrack.git
   cd aquatrack
   ```

2. **Open the application**
   - Simply open `index.html` in your preferred web browser.  
   - No build steps, dependencies, or server required!

3. **Optional – Use Live Server**  
   If you have VS Code, install the “Live Server” extension and right‑click `index.html` → “Open with Live Server” for auto‑refresh during development.

## 🌐 Deployment

You can deploy AquaTrack instantly using **GitHub Pages**:

1. Push the repository to GitHub.
2. Go to **Settings** → **Pages**.
3. Under “Branch”, select `main` (or `master`) and save.
4. Your app will be live at `https://yourusername.github.io/aquatrack/`

Alternatively, host it on any static hosting service like Netlify, Vercel, or Render.

## 📖 Customization

- **Change default daily goal** – Modify the `value` attribute of the input with ID `dailyGoalInput` (line ~210 in the HTML).  
- **Adjust quick add options** – Edit the `<select id="quickSelect">` options (values in liters).  
- **Modify color theme** – Update CSS variables or gradient definitions in the `<style>` section.  
- **Extend chart to 14 days** – Change the `getLast7Days()` function logic and adjust the chart labels.

## 🤝 Contributing

Contributions are welcome! If you have ideas for new features (e.g., monthly reports, CSV export, notifications), feel free to:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-idea`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-idea`)
5. Open a Pull Request

Please ensure your code follows the existing style and does not break core functionality.

## 📄 License

Distributed under the **MIT License**. See `LICENSE` file for more information.

## Acknowledgments

- [Chart.js](https://www.chartjs.org/) for the simple and powerful charting library.
- [Font Awesome](https://fontawesome.com/) for the crisp icons.
- [Google Fonts](https://fonts.google.com/) for the Inter typeface.

## 📧 Contact

Your Name – [@yourtwitter](https://twitter.com/yourtwitter) – email@example.com  
Project Link: [https://github.com/yourusername/aquatrack](https://github.com/yourusername/aquatrack)

---

⭐ **If you find AquaTrack useful, please give it a star on GitHub!**  
Made with 💧 and ☕ for a healthier, more hydrated world.
```

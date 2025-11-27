# 🌍 VoyageFlow — Interactive Travel Experience Simulator

VoyageFlow is a **4-page simulated travel experience website** built entirely using **HTML5, CSS3, and Vanilla JavaScript (ES6+)**. It guides users through a realistic journey of:

1. **Registration** (with validation and custom modal)
2. **Travel blog browsing** (smooth scrolling + sticky navbar)
3. **Trip planner with real-time price calculation**
4. **Final confirmation page**

All pages are simulated inside **one HTML file** using `show/hide` containers, making the project ideal for static hosting like **GitHub Pages**.

---

## 🏁 Live Demo

**GitHub Pages Link:**
*(Add after deployment)*
`https://oyy-krishna.github.io/voyageflow/`

---

## 📌 Features

### ✅ Page 1 — Registration Form

* Validates **Phone (10 digits)**, **PIN Code (6 digits)**, and **Email format**
* Real-time or on-submit validation
* Displays errors under inputs
* On success → Shows a **custom modal** → Navigates to Page 2

### ✅ Page 2 — Travel Blog & Destinations

* Minimum **5 content sections** (e.g., Paris, Tokyo, Rome)
* **Sticky navbar** with anchors
* **Smooth scrolling** to each section
* “Next” button to go to Page 3

### ✅ Page 3 — Trip Planner & Price Calculator

* Select options: Travel, Food, Activities
* Each option has a fixed price (static data)
* **Instant total price calculation** on every checkbox click
* Confirmation modal before moving to Page 4

### ✅ Page 4 — Final Confirmation Page

* “Thank You” message
* Aesthetic closing screen
* Optional: social links, restart button

---

## 🛠️ Technologies Used

* **HTML5** – Page structure, content containers
* **CSS3** – Responsive design, modals, layouts
* **JavaScript ES6+** – Validation, modal control, price calculation, navigation simulation
* **Optional:** Tailwind CSS CDN (if styling was improved using it)

---

## 📁 Project Structure

```
voyageflow/
│
└── index.html        # Contains all 4 simulated pages
```

> *The entire website runs from a single HTML file using hidden sections.*

---

## 🚀 How to Run Locally

1. Download the project or clone the repo:

   ```bash
   git clone https://github.com/oyy-krishna/voyageflow.git
   ```
2. Open `index.html` in any modern browser.
3. Everything works without a server — fully client-side.

---

## 🌐 Deployment on GitHub Pages

1. Go to **Settings → Pages**
2. Under **Source**, select:

   * **Branch:** `main`
   * **Folder:** `/ (root)`
3. Save → GitHub Pages will generate your site in 20–60 seconds.

Your website will be live at:
`https://<username>.github.io/voyageflow/`

---

## 📸 Screenshots (Optional)

> Add screenshots here before uploading to GitHub.

---

## ✨ Author

**Krishan Bhati**
VoyageFlow — A project showcasing multi-page simulation using only front-end technologies.

---

## 📬 Want Improvements?

Feel free to request features like:

* Multi-file structure
* Tailwind UI version
* Dark mode
* Animations
* Better travel cards

---

Made with ❤️ for learning and creativity.

# 🌍 VoyageFlow

A clean, responsive, and elegant travel itinerary planner interface designed for **VoyageFlow** — a minimal travel planning platform that helps users explore destinations, choose interests, and begin their journey effortlessly.

---

## 🚀 Live Demo

Once deployed on GitHub Pages, the project will be available here:
**[https://oyy-krishna.github.io/voyageflow/](https://oyy-krishna.github.io/voyageflow/)**

---

## 📌 Features

* ✨ Clean and modern UI
* 📸 Hero section with gradient overlay
* 🎒 Interest selection badges
* 🏖️ Popular destinations with ratings
* 🖼️ Optimized for travel-based content
* 📱 Fully responsive layout

---

## 🧩 Tech Stack

* **HTML5**
* **CSS3**
* **Tailwind CSS** (via CDN)
* **Lucide Icons** for minimal, modern icons

---

## 📂 Project Structure

```
voyageflow/
│── index.html
│── (images/ – if you add custom images)
│── README.md
```

---

## 🛠️ How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/oyy-krishna/voyageflow.git
```

2. Navigate to the folder:

```bash
cd voyageflow
```

3. Open `index.html` in your browser.

---

## 🌐 Hosting with GitHub Pages

1. Go to **Settings → Pages**
2. Set **Branch: main** and **/ (root)** folder
3. Click **Save**
4. Access your site at:

```
https://oyy-krishna.github.io/voyageflow/
```

---

## 📸 Screenshots

*Add screenshots of your final UI here for better presentation.*

```
images/
   ├─ homepage.png
   ├─ destination-section.png
```

---

## 👨‍💻 Author

**Krishan Bhati**
VoyageFlow by oyy-krishna

---

## ⭐ Want to Contribute?

Pull requests are welcome! If you’d like to enhance animations, add components, or redesign elements — feel free to contribute.

---

## 📝 License

This project is licensed under the **MIT License**.

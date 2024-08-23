
---

# Heartbeat Clock

A simple and elegant digital clock that displays the current time using heart symbols in a 5x5 grid format. The clock features customizable background videos including options like a serene ocean dive, a playful dog, and an amusing monkey to enhance the visual appeal.

## 📋 Table of Contents

- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [Contact](#contact)

---

## ⭐ Features

- **Heart Grid Time Display**: Shows the current time with heart symbols arranged in a 5x5 grid for each digit.
- **Dynamic Background Videos**: Switch between different background videos (Buceo, Dog, Monkey) to set the ambiance.
- **Responsive Design**: Ensures optimal viewing experience across various devices and screen sizes.
- **Interactive Controls**: Easy-to-use buttons to change background videos seamlessly.
- **Lightweight and Fast**: Minimalistic design for quick load times and smooth performance.

---

## 🎥 Demo

[![Heartbeat Clock Demo](./assets/demo.gif)](#)

---

## 🛠️ Installation

Follow these steps to set up the project locally:

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/heartbeat-clock.git
   ```
2. **Navigate to the project directory**
   ```bash
   cd heartbeat-clock
   ```
3. **Open `index.html` in your preferred browser**
   - You can simply double-click the `index.html` file or serve it using a local server for better performance.
   
---
## 🚀 Usage

- **Changing Background Videos**
  - Click on the buttons labeled **Buceo**, **Dog**, or **Monkey** to switch between different background videos.
  
- **Time Display**
  - The clock automatically updates every second to display the current time using heart symbols.
  
- **Adding New Background Videos**
  1. Place your video file in the `assets` folder.
  2. Add a new button in the HTML with an appropriate label.
     ```html
     <button onclick="changeVideo('assets/YourVideo.mp4')">Your Video</button>
     ```
  3. The `changeVideo` function will handle the rest.

---

## 💻 Technologies Used

- **HTML5**: Structuring the content of the web page.
- **CSS3**: Styling and layout design.
- **JavaScript (ES6)**: Implementing interactive features and clock functionality.
- **Bootstrap 5**: Responsive design and prebuilt components.
- **Video Media**: MP4 videos for dynamic backgrounds.

---

## 📁 Project Structure

```
heartbeat-clock/
├── assets/
│   ├── Buceo.mp4
│   ├── Dog.mp4
│   └── Monkey.mp4
├── index.html
├── style.css
└── README.md
```

- **assets/**: Contains all media files used in the project.
- **index.html**: The main HTML file that structures the webpage.
- **style.css**: Stylesheet for custom styling.
- **README.md**: Documentation and project overview.

---

## 🤝 Contributing

Contributions are welcome! Follow these steps to contribute:

1. **Fork the repository**
2. **Create a new branch**
   ```bash
   git checkout -b feature/YourFeature
   ```
3. **Make your changes and commit**
   ```bash
   git commit -m "Add your message"
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/YourFeature
   ```
5. **Open a Pull Request**


---

## 📞 Contact

**Your Name**
- **Email**: andreamelissa.tc@gmail.com
- **GitHub**: [andrea13-12](https://github.com/andrea13-12
)
- **LinkedIn**: [Andrea Torres](https://www.linkedin.com/in/andrea-torres-cerdan/)

Feel free to reach out for any questions or collaboration opportunities!

---
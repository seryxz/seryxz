```javascript
class AboutMe {
  constructor() {
    this.name = "Serhii";
    this.role = "Computer Science Student & Frontend Enthusiast";
    this.focus = ["Bootstrap", "Tailwind CSS", "HTML", "CSS", "JavaScript"];
    this.languages = ["English 🇬🇧", "German 🇩🇪"];
    this.interests = ["Programming 💻", "Language Learning 📚", "Web Development 🌐"];
    this.dailyHours = 6;
    this.energy = 0.85; // 0 = sleepy, 1 = hyper
    this.motto = "Turning coffee ☕ into clean, bug-free code 🐞✨";
  }

  progressBar(percent = this.energy) {
    const width = 20;
    const filled = Math.round(percent * width);
    const empty = width - filled;
    return "[" + "█".repeat(filled) + " ".repeat(empty) + `] ${Math.round(percent * 100)}%`;
  }
}

const me = new AboutMe();

# Web Styling Lab

CSS customization project featuring a Reddit theme and a styled interactive story.

Author: Fatima Navarro  
Course: Web Systems and Technologies  
Universidad del Valle de Guatemala - 2026

---

## Project Overview

This project consists of two parts:

1. Reddit Custom Theme - A retro-styled theme using Stylus
2. The Fox's Odyssey - CSS styling for an interactive choose-your-adventure story

---

## Part 1: Reddit Custom Theme

### Description
Custom CSS theme for Reddit with soft retro aesthetic and pastel colors.

### Color Palette
- Background: #fef5f7 (soft pink)
- Header: #695b5b (brown)
- Posts: #695b5b (brown with rounded corners)
- Buttons: #86cecb (turquoise)
- Accents: #e12885 (pink)

### Installation

1. Install Stylus browser extension
2. Go to reddit.com
3. Click Stylus icon and select "Write style for: reddit.com"
4. Copy CSS from RedditStylus/style.css
5. Save and refresh Reddit

### Screenshots

Before:
<img width="1192" height="724" alt="image" src="https://github.com/user-attachments/assets/d06b3dec-9932-49f2-a870-e29d11fea435" />


After:
<img width="1192" height="724" alt="image" src="https://github.com/user-attachments/assets/7ad74ba8-fba2-4888-b14e-87543abbe3b1" />


---

## Part 2: The Fox's Odyssey

### Description
Interactive story with professional CSS styling including dynamic backgrounds, styled images, and game-like buttons.

### Features

Different background colors for each section:
- Starting page: Forest green gradient
- Chapter pages: Earthy brown gradient
- Good ending: Golden gradient
- Neutral ending: Blue-gray gradient
- Bad ending: Dark red gradient

Visual elements:
- Images with borders and shadows
- Game-style interactive buttons
- Hover animations on links
- Georgia serif typography

### File Structure
```
.
├── RedditStylus/
│   └── style.css
├── css/
│   └── styles.css
├── inicio/
│   └── index.html
├── capitulos/
│   └── (13 chapter files)
├── finales/
│   ├── final_bueno.html
│   ├── final_neutro.html
│   └── final_malo.html
├── imagenes/
└── README.md
```

---

## Running Locally

### Option 1: Direct File Access
```bash
git clone <repository-url>
cd lab2-web-styling
open inicio/index.html
```

### Option 2: NGINX Server

1. Create directory:
```bash
sudo mkdir -p /var/www/html/lab2
```

2. Copy files:
```bash
sudo cp -r * /var/www/html/lab2/
```

3. Set permissions:
```bash
sudo chmod -R 755 /var/www/html/lab2
```

4. Access in browser:
```
http://localhost/lab2/inicio/
```

---

## Technologies Used

- HTML5
- CSS3
- NGINX (for deployment)

---

## Requirements Met

Part 1 - Reddit Theme:
- Custom CSS theme using Stylus
- Saved in RedditStylus folder
- Before/after screenshots in README

Part 2 - Story Styling:
- Consistent design throughout
- Custom typography (Georgia serif)
- Different background colors for inicio, capitulos, and finales
- At least one animation (hover effect with translateX)
- Images with borders and specific sizing
- Game-style buttons (Skyrim/Fallout inspired)
- Running from NGINX

Additional Requirements:
- Public Git repository with daily commits
- No JavaScript used
- CSS in separate folder, linked to HTML files
- No inline CSS
- English README with instructions

---

## Video Demo

(Add link to video demonstration)

---

## License

Universidad del Valle de Guatemala - Academic Project 2026


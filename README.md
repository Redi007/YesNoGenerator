# Themed Decision Maker

A visually dynamic yes/no decision-making web app with multiple animated themes, interactive elements, and persistent theme preferences.

---

## Features

✅ **6 Unique Themes**:
- **Matrix**: Falling green code  
- **Blossom**: Floating flower petals  
- **Modern**: Glowing lines and nodes  
- **Dark Mode**: Starry night sky  
- **Peach**: Peach/leaf animations  
- **Skyblue**: Rising bubbles  

✅ **Interactive Animations**: Background effects respond to theme selection  
✅ **Decision Generator**: Random YES/NO results with animated spinner  
✅ **Persistent Preferences**: Saves selected theme via localStorage  
✅ **Result Counter**: Tracks YES/NO history  
✅ **Responsive Design**: Works on all screen sizes  

---

## How to Use

1. **Select Theme**: Choose from the dropdown in the top-right corner  
2. **Generate Answer**: Click the "Generate Answer" button  
3. **View Results**: Watch the animated spinner and see the outcome  

---

## Technical Details

- Built with HTML/CSS/JavaScript  
- Uses CSS variables for theme management  
- Dynamic background elements generated via JavaScript  
- Smooth animations using CSS keyframes  
- Lightweight (no dependencies)  

---

## Customization

### 1. Add New Themes:
   - Create a new `[data-theme="your-theme"]` CSS block  
   - Define `--primary`, `--bg`, `--text`, and `--accent` colors  
   - Add background animation logic in `createBackground()`  

### 2. Modify Animations:
   - Adjust keyframe animations in CSS  
   - Tweak JavaScript parameters for element generation  

---

## Screenshots

*(Add screenshots here showing different themes)*  

---

## License

MIT License - feel free to modify and redistribute

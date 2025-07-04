# 🍎 Tracalorie - Calorie Tracker App

A simple web app to track daily calorie intake and burn.

> 📚 **Learning Project from**: Modern JavaScript from The Beginning [Second Edition] - Packt
> 🎯 **Course Focus**: ES6+, DOM Manipulation, Local Storage, OOP with Classes

## 📖 About This Learning Project

### 🔧 Key Concepts Demonstrated

- **Static Methods**: Used in Storage class for data operations
- **Private Fields**: Modern JavaScript class privacy (`#property`)
- **Event Delegation**: Efficient event handling for dynamic content
- **State Management**: Tracking app state and updating UI accordingly
- **Responsive Design**: Mobile-first approach with CSS Grid/Flexbox

### 🌟 Enhanced Features (Beyond Course)

- **Multiple UI Versions**: Classic and Cute interfaces
- **Mobile Optimization**: Touch-friendly interface for all devices

## 🎯 Main Features

- ✅ Add/remove meals
- ✅ Add/remove workouts
- ✅ Set daily calorie limit
- ✅ Filter meals/workouts list
- ✅ Reset all data
- ✅ Auto save data

## 🌈 UI Versions

### 1. **Classic Version**

- **File**: `index-classic.html`
- **Style**: Simple Bootstrap design
- **Good for**: Users who like basic, traditional interface

### 2. **Cute Version**

- **File**: `indexES2022.html` 
- **Style**: Sweet design, pastel colors
- **Good for**: Users who like cute, friendly interface

## 🚀 How to Use

1. **Open HTML file** you want to use
2. **Set calorie limit**: Click "Set Limit"
3. **Add meals**: Click "Add Meal" → enter name and calories
4. **Add workouts**: Click "Add Workout" → enter name and calories
5. **Delete items**: Click delete button on each item
6. **Filter list**: Type in search box
7. **Reset**: Click "Reset" to clear all data

## 📱 Quick Start

```bash
# Open cute interface
double-click index-cute.html

# Or open classic interface
double-click indexES2022.html
```

## 🛠️ File Structure

```
📁 tracalorie-app/
├── 🌸 indexES2022.html         # Cute interface
├── 📝 index.html               # Classic interface
├── 📁 js/
│   ├── indexES2022.js          # Logic for cute version using ES2022
│   ├── index.js                # Logic for classic version
├── 📁 css/
│   ├── cute-ui.css             # Style for cute version
│   └── style.css               # Basic style
└───   README-USAGE.md          # This file
```

## 💡 Notes

- Data is auto saved in browser
- To clear data: Reset or clear localStorage
- App works offline (no internet needed)
- Responsive design - works on mobile

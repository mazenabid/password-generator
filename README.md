# Password Generator
<div align="center">
<img src="https://github.com/user-attachments/assets/5f5a3d9a-5cc7-4022-84c7-a0f98db32ca1" width="800"/>
</div>
<div align="center">
A simple, interactive password generator with dark mode support
</div>

## Features

**Generate Passwords** - Click the button to create two random 15-character passwords  
**Copy to Clipboard** - Click any password to copy it (shows "Copied!" confirmation)  
**Dark Mode** - Toggle between light and dark themes  
**Interactive UI** - Button presses in when clicked, password boxes highlight on hover  

## How to Use

1. Click **"Generate Password"** to create random passwords
2. Click a password box to copy it to your clipboard
3. Use **"Light / Dark Mode"** button to switch themes

## Installation

```bash
npm install
npm run dev
```

## Customization

To change password length, edit line 14 in `index.js`:
```javascript
for (let i = 0 ; i < 15 ; i++) {  // Change 15 to desired length
```
## Characters
To modify password characters, edit the `characters` array at the top of `index.js`.
```javascript
const characters = ["A","B","C","D","E","F","G","H","I","J","K","L","M","N","O","P","Q","R","S","T","U","V","W","X","Y","Z","a","b","c","d","e","f","g","h","i","j","k","l","m","n","o","p","q","r","s","t","u","v","w","x","y","z", "0", "1", "2", "3", "4", "5", "6", "7", "8", "9","~","`","!","@","#","$","%","^","&","*","(",")","_","-","+","=","{","[","}","]",",","|",":",";","<",">",".","?",
"/"]
```

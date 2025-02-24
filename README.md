### 1. **Console Commands**
Use your browser’s developer tools to run these cheats:

#### Add Cookies
```javascript
// Instantly add 1,000,000 cookies
Game.cookies += 1000000;
```

#### Unlock All Upgrades
```javascript
// Unlock every upgrade
Game.UpgradesById.forEach(upgrade => upgrade.unlock());
```

#### Unlock All Achievements
```javascript
// Unlock every achievement
Game.AchievementsById.forEach(achievement => achievement.unlock());
```

### 2. **Bookmarklet Hacks**
Simplify cheating by creating a bookmark that runs a command when clicked:

#### Infinite Cookies
```javascript
javascript:(function(){Game.cookies=999999999;})();
```

#### Auto-Buy Buildings
```javascript
javascript:(function(){Game.ObjectsById.forEach(obj => obj.amount += 100);})();
```

### 3. **Save File Editing**
Edit your save file for complete customization:

1. Go to the **Settings** menu and click **Export Save**.
2. Copy the save text and paste it into a text editor.
3. Modify values like `Game.cookies` or `upgrades`.
4. Import the edited save back into the game.

#### Example Save File Edits
- Set cookies to an absurdly high amount:
  ```text
  "Game.cookies=1e+300;"
  ```
- Unlock all upgrades and achievements by modifying the save text.

### 4. **Third-Party Tools**
Explore tools and extensions designed for **Cookie Clicker cheats**:

- **[CCBot](https://github.com)**: Automates clicking and optimizes upgrades.
- **Tampermonkey Scripts**: Install custom scripts for additional cheats and quality-of-life improvements.

### 5. **Advanced Console Hacks**
For players looking to push the game’s limits, try these advanced hacks:

#### Spawn Golden Cookies
```javascript
// Instantly spawn a golden cookie
Game.shimmerTypes.golden.spawn();
```

#### Accelerate Time
```javascript
// Simulate one hour of gameplay
Game.Earn(1000000000); // Replace with desired cookie amount
Game.ClickCookie();
```

#### Adjust Building Prices
```javascript
// Set all building costs to 1 cookie
Game.ObjectsById.forEach(obj => obj.basePrice = 1);
```

### 6. **Mods and Extensions**
Install mods for a fully customized experience:

- **Cookie Monster**: Displays detailed stats and production metrics.
- **Frozen Cookies**: Automates gameplay with optimized strategies.

## ⚠️ Important Notes
- Using cheats and hacks can change your gaming experience. Use responsibly.
- Always back up your save file before applying any cheats.
- Certain cheats may disable achievements or affect future updates.

## 📚 Additional Resources
- [Cookie Clicker Wiki](https://cookieclicker.fandom.com/wiki/Cookie_Clicker_Wiki): In-depth details about the game.
- [Official Cookie Clicker Website]([https://orteil.dashnet.org/cookieclicker/](https://cookieclicker.me/)): Play the latest version.
- [Reddit Community](https://www.reddit.com/r/CookieClicker/): Share strategies and tips with other players.

## 🤝 Contributing
Have a new cheat or hack to share? Submit a pull request or open an issue. Contributions are welcome!

## 📝 License
This project is licensed under the MIT License. See the LICENSE file for details.

---

**Disclaimer**: This repository is for educational purposes only. The cheats and hacks provided here are intended for personal use and should not disrupt others’ gameplay experiences.

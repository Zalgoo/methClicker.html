# Walter White Clicker

Welcome to the **Walter White Clicker**! This is an incremental idle game where you, as Walter White, produce "meth" (in-game currency) to buy upgrades and expand your criminal empire. Click the button to produce meth, purchase upgrades to increase your production, and "commit crime" to gain permanent boosts.

---

## How to Play

The game is simple and addictive:

* **Click for Meth!**: Click the big blue button to manually produce meth. The amount you get per click is your **MPC (Meth Per Click)**.
* **Buy Upgrades**: Use your meth to buy upgrades from the "Upgrades" section. These upgrades can increase your MPC or your **MPS (Meth Per Second)**, which automatically generates meth for you even when you're not clicking.
* **Commit Crime!**: This is the "rebirth" mechanic. When you have enough meth, you can commit a crime to reset your game progress (meth, upgrades, MPC, and MPS). In return, you'll gain a **Criminal Charge**. Criminal Charges unlock powerful, permanent upgrades that will help you progress faster in your next playthrough.
* **Offline Production**: Your labs will continue to produce meth while you're away! When you return to the game, a modal will pop up, offering you the meth you earned offline.

---

## Features

* **Responsive Design**: The game is built with Tailwind CSS, ensuring a clean and responsive interface on both desktop and mobile devices.
* **Idle Gameplay**: The game features an MPS system, allowing you to earn meth passively.
* **Rebirth System**: The "Commit Crime" mechanic provides a layer of strategic depth, encouraging you to reach certain goals to unlock permanent bonuses.
* **Persistent Save**: Your game progress is automatically saved to your browser's local storage every 5 seconds and when you close the tab, so you can pick up where you left off.
* **Background Music**: A looping background track enhances the immersive experience, with a volume slider for user control.

---

### Chrome DevTools Commands

For developers and power users, you can use the browser's console to manually adjust your game stats.

| Command         | Description                                     |
| :-------------- | :---------------------------------------------- |
| `meth = amount` | Sets your current meth count to a specific amount. |
| `mpc = amount`  | Sets your Meth Per Click to a specific amount.  |
| `mps = amount`  | Sets your Meth Per Second to a specific amount. |

---

## Technologies Used

| Technology              | Description                                                                                             |
| :---------------------- | :------------------------------------------------------------------------------------------------------ |
| **HTML5** | For the basic structure of the game.                                                                    |
| **CSS3** | Custom styles for modal windows and hover effects.                                                      |
| **Tailwind CSS** | A utility-first CSS framework for rapid UI development.                                                 |
| **JavaScript (ES6+)** | Powers all the game logic, including the clicker, upgrades, save/load functionality, and the rebirth system. |

---

## Assets

| Asset Type         | File Path                 | Description                                    |
| :----------------- | :------------------------ | :--------------------------------------------- |
| **Background Music** | `assets/bg-Music.ogg`     | A looping audio track for the game's background. |
| **Sound Effect** | `assets/Walta.mp3`        | A sound effect for in-game actions.             |
| **Image** | `https://static1.srcdn.com/wordpress/wp-content/uploads/2020/02/Breaking-Bad-things-Walter-White-feature.jpg` | A public-domain image of Walter White used in the game. |

---

## How to Run

1.  Clone or download this repository.
2.  Ensure you have the `assets` folder with `bg-Music.ogg` and `Walta.mp3` in the same directory as `meth.html`.
3.  Open the `meth.html` file in your preferred web browser.

No server is required to run this game, as all the code is client-side.

## Preview:
![example.png](https://raw.githubusercontent.com/ackozu/meth-clicker/refs/heads/main/example.png)

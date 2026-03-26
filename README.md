# pacman_simugame2

A simple browser-based Pac-Man game built in a single `index.html` file (~120 lines).

## Summary

This is the **easiest and fastest** of the three Pac-Man builds — a 5-minute prompt compared to the other two:

| Repo | Approach | Complexity |
|------|----------|------------|
| **pacmann** | JSX → HTML conversion | High |
| **pacman_simugame** | Plain HTML | Medium |
| **pacman_simugame2** | Plain HTML (this one) | Low — built in ~5 mins |

---

## Prompts Used in This Session

**Prompt 1 — Build the game:**
> Create a single index.html file in the root of this repo. Keep it under 200 lines total.
> Simple Pac-Man game requirements:
> - Small 15x15 grid maze drawn with canvas
> - Pac-Man moves forward by turning with arrow keys
> - 2 ghosts that bounce around randomly
> - Dots to eat, score counter
> - Press ENTER to start (not SPACE)
> - Game over when ghost touches Pac-Man
> - Black background, yellow Pac-Man, blue walls
>
> Important: Use requestAnimationFrame for the game loop. Do NOT use setInterval. Arrow keys must work immediately on page load after clicking ENTER to start the game.
> Commit and push directly to main branch.

**Prompt 2 — Add win condition:**
> After Pac-Man finish eating the dots, End Game and shows "YOU WIN!"

**Prompt 3 — Add README:**
> Please create a readme.md, includes the prompts in this session.
> summary should be this prompt is easy game to build one in 5 mins compared to the other two pacman game (pacmann: JSX to HTML, pacman_simugame: HTML)

---

## How to Play

1. Open `index.html` in a browser
2. Press **ENTER** to start
3. Use **arrow keys** to steer Pac-Man
4. Eat all dots to **win**, avoid ghosts or it's **game over**
5. Press **ENTER** to restart at any time

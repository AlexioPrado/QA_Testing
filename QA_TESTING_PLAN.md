# Game Being Tested: Christopher-Rise-Of-Mark-Ham
**Dev Team:** Gabe, Rahul, Huzaifah, Troy - Gcc07/Christofer  
**QA Team:** Christopher, Afton, Angel, Marcus  
**Date:** 2/10/2026  

**Game Type:** Text-based dungeon crawler RPG with roguelike elements  

## Core Mechanics:
1. Random character generation  
2. Multiple room types  
3. Wide variety of weapons and consumables  
4. Time-based combat  
5. Bosses  

## Win Condition:
- Beat the final boss and make it past floor 30  

## Lose Condition:
- Die in a battle or quit  

## Player Inputs:
- 0-9, and specific text input (EX: Continue YES or NO, Input: “NO”)  

---

## Testing Strategy

### Tuesday:
**Goal:** Define all probable bugs, test three bugs, then move on so we can get to the other games  

**Test Scenarios:**
- Test input outside given options (Ex: Input 1 or 2. User inputted 3)  
- Tested negative speed  
- Tested spam  

**Known: issue found today:**
- On the start menu inputting a number that is not 1-2 jumps straight into the game which is not intended. Invalid input check (Severity: Medium, Priority: )  
- If you spam input while text is being displayed your input affects the next input checks. This stacks and can break the game (Severity: High, Priority: )  
- Setting text speed to a negative number and playing the game crashes it. No check/validation for negative speed (Severity: Critical, Priority: )  
- When in Menu, selecting 3 will return instead of going to information codex (Severity: High, Priority: High)  
- When adjusting text speed, it is not consistent to all (Severity: Low, Priority: Low)  

### Wednesday:
**Goal:** Define all complex bugs  

**Test Scenarios:**
- After attempting to use moon blessing following text is shaded incorrectly  
- Attempting to use an item you don't have (like 4) crashes  
- Setting a faster text speed makes dialogue slower  

**Known: issue found today:**
- After attempting to use moon blessing the actions are a darker shade of gray instead of the white it usually is.  
- When using an item if you input a number out of range for valid items it crashes  
- After setting text speed to a higher number like 200 dialogue becomes way slower  

---

## Summary Table
| Day  | Bugs Found | Critical | High | Medium | Low | Total |
|------|-----------|----------|------|--------|-----|-------|
| Tue. | 5         | 1        | 2    | 1      | 1   | 5     |
| Wed. | 3         | 1        | 0    | 0      | 2   | 3     |
| Total| 8         |          |      |        |     | 8     |

---

## Notes
**Testing Environment:** Java In Terminal  
**Any blockers or issues with the game code itself?** None. We love this group.  
**Assumptions:** None  

---

## Recommendations for Dev Team

### Critical bugs to fix first:
- Negative text speed crashes the game  
- Using an item out of range crashes the game  

### High-priority fixes:
- Spamming valid inputs while text is being written causes prolonged inputs after text stops writing.  

### Nice-to-have fixes:
- Invalid number inputs on the start menu cause the game to jump straight into the game. Undesired behavior  
- Using moon blessing sets text to wrong shade of gray  
- High text speed makes dialogue speed extremely slow  

**Testing completed by:** Christopher  
**Date submitted:** 2/12/2026  

---

---

# Game Being Tested: Fshng
**Dev Team:** Evan Yango, Marcus Ceradini, Bianca Baccay, Ayah Abdalla, Maddy Puryear,  
**QA Team:** Christopher, Afton, Angel, Marcus  
**Date:** 2/10/2026  

**Game Type:** Fishing Arcade  

## Core Mechanics:
- None listed!  

## Win Condition:
- Get the highest score and feed as much sharks as possible  

## Lose Condition:
- Fail to get the required amount of fish  

## Player Inputs:
- Mouse Left/Right Click  

---

## Testing Strategy -

### Tuesday:
**Goal:** Define all probable bugs, Test three bugs then move on so we can get to the other games  

**Test Scenarios:**
- Game starts at round 2  
- Fishing rod and fish fly off screen when you resurface  
- No lose condition  

**Known: issue found today:**
- When booting the game the round started at 2. Unintended behavior  
- When surfacing with multiple fish the rod and fish flew to the top right of the screen without user input. Unintended behavior  
- Repeatedly catching no fish does not yield a loss. Unintended behavior  

### Wednesday:
**Goal:** Test for extra bugs  

**Test Scenarios:** Visual work correctly  

**Known Issues:**
- We don’t know the weight of the fish so we cant make sure the pound are calculated correctly  

---

## Summary Table
| Day   | Bugs Found | Critical | High | Medium | Low | Total |
|-------|------------|----------|------|--------|-----|-------|
| Tue.  | 3          | 0        | 1    | 0      | 2   | 3     |
| Wed.  | 1          | 0        | 0    | 0      | 1   | 1     |
| Total | 4          | 0        | 1    | 0      | 3   | 4     |

---

## Notes
**Testing Environment:** Pygame  
**Any blockers or issues with the game code itself?** None  
**Assumptions:** None  

---

## Recommendations for Dev Team -

### High-priority fixes:
- No lose condition  

### Nice-to-have fixes: [Lower priority issues]
- Start at round 1  
- Make fish no longer fly off the screen  
- Know the weight of the fish  

**Testing completed by:** Christopher Markham  
**Date submitted:**2/12/2026  

---

---

# Game Being Tested: Echo of Terminal 7
**Dev Team:** Nayan, Khani Gauhar, Quint - Q456lm/sprint1  
**QA Team:** Christopher, Afton, Angel, Marcus  
**Date:** 2/10/2026  

**Game Type:** Top Down Sci-fi puzzle adventure  

## Core Mechanics:
1. Room exploration (2D)  
2. Interactable environment  
3. Mini games & Boss fights  

## Win Condition:
- Power is restored  
- The Herd secret is understood  

## Lose Condition:
- None/Exit the game  

## Player Inputs:
- WASD, Up, Left, Down, Right, E, Mouse Left Click, ESC  

---

## Testing Strategy

### Tuesday:
**Goal:** Define all probable bugs, test three bugs, then move on so we can get to the other games  

**Test Scenarios:**
- The green button on the power grid puzzle is unclickable  
- Bio-Lab puzzle is completed upon starting the game  
- Admin Console password does not work  

**Known: issue found today:**
- In the power grid puzzle, you can’t select the green box.  
- The bio-lab puzzle starts complete,d meaning you can't solve it.  
- Inputting the correct password, “They are in the herd.” does not do anything, making the puzzle unsolvable  

---

## Summary Table
| Day   | Bugs Found | Critical | High | Medium | Low | Total |
|-------|------------|----------|------|--------|-----|-------|
| Tue.  | 3          | 2        | 1    | 0      | 1   | 3     |
| Total | 3          | 2        | 1    | 0      | 1   | 3     |

---

## Notes
**Testing Environment:** Pygame  
**Any blockers or issues with the game code itself?** None  
**Assumptions:** None  

---

## Recommendations for Dev Team

### Critical bugs to fix first:
- Allow the correct admin password to unlock the admin console  
- Make the green button in the power grid able to be clicked  

### High-priority fixes:
- Make it so the bio-lab puzzle does not start completed and must be solved by the user  

### Nice-to-have fixes:
- An input to skip the loading of the start text and another input to start. This avoids accidentally skipping straight to the game.  

**Testing completed by:** Christopher Markham  
**Date submitted:** 2/12/2026  

---

---

# Game Being Tested: BlackJack
**Dev Team:** Samuel, Jessica, Karan, Maxwell - mcnoffersinger/BlackJack  
**QA Team:** Christopher, Afton, Angel, Marcus  
**Date:** 2/10/2026  

**Game Type:** Card game  

## Core Mechanics:
1. Player can Stand or Hit each round to play BlackJack  
2. Full Deck of cards is simulated to correctly deal random cards  
3. Player can customize their bet at the start of each round  
4. Pygame visuals (if we can get it to work)  
5. Player can select AI difficulty and unlock extra cards by playing rounds.  
6. Russian roulette mode  

## Win Condition:
- If the user gets a hand with the value of 21  
- If the user gets a hand with a value higher than the dealer's but not over 21  
- The player gains the amount of money they bet and can play again  

## Lose Condition:
- If the user gets a hand over the value of 21  
- If the player gets a hand with a value lower than the dealer's and the dealer's value is not over 21  
- The player loses the amount of money they bet and is shown the loss screen.  

## Player Inputs:
- User will only use their mouse clicker to make decisions during the game.  

---

## Testing Strategy

### Tuesday:
**Goal:** Define all probable bugs, test three bugs, then move on so we can get to the other games  

**Test Scenarios:**
- No check to prohibit bets if you have no money  
- No money makes the minus button add $10 to the bet.  
- Spamming the hit or stand button when in Russian mode closes the game  

**Known: issue found today:**
- When you have no money, you can still bet.  
- When you have no money, clicking the minus on the bet sets the bet to $10, thus increasing the bet. After this, clicking the plus button reverts the bet back to $0, thus decreasing the bet.  
- Selecting Russian mode and spamming the hit or stand button causes the game to close. This soft-locks you.  

---

## Summary Table
| Day   | Bugs Found | Critical | High | Medium | Low | Total |
|-------|------------|----------|------|--------|-----|-------|
| Tue.  | 3          | 1        | 0    | 2      | 0   | 3     |
| Total | 3          | 1        | 0    | 2      | 0   | 3     |

---

## Notes
**Testing Environment:** Pygame  
**Any blockers or issues with the game code itself?** None  
**Assumptions:** None  

---

## Recommendations for Dev Team

### Critical bugs to fix first:
- Betting on Russian mode soft locks you, as any repeated input will crash the game.  

### Nice-to-have fixes: [Lower priority issues]
- Make it so you can’t bet money you don't have.  
- Make it so that when you have no money, you can’t set the bet to $10 by clicking the minus bet button.  

**Testing completed by:** Christopher Markham  
**Date submitted:** 2/12/2026  

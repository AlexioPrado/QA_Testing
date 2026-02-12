# QA Testing Report – Week 2

# Game Tested: Christopher: The Rise of Mark-Ham
**Dev Team:** Gabe, Rahul, Huzaifah, Troy  
**Repo:** Gcc07/Christofer-Rise-Of-Mark-Ham/repo  
**QA Team:** Angel, Afton, Christopher, Marcus  
**Testing Period:** Week 2  
**Report Date:** 2/10/2026  

## Executive Summary

Over 2 days we conducted comprehensive QA testing of the game *Christopher*. Our team tested all core features and found a total of **8 issues**.

**Key Finding:** There seems to be no validation for invalid input in multiple areas.

## Testing Overview
### What We Tested

- Happy path (normal gameplay) ✓  
- Input validation & edge cases ✓  
  - Tested numbers around valid inputs  
  - Tested random characters  
- Win/lose conditions ✓  
  - Tested dying and winning  
- State management ✓  
- Complex scenarios & sequences ✓  

## Coverage Summary
### Features Tested
- User input validation: **90%**
- Using items: **70%**
- Adjusting settings: **100%**

### Test Types
- **Functional Testing** (Does it work?)  
  - Yes  
- **Negative Testing** (What breaks it?)  
  - Out of bounds input  
  - Spamming  
- **Boundary Testing** (Edge values)  
  - Out of bounds input  
  - Spamming  
- **Exploratory Testing**  
  - Setting text speed to 0
    
## Bug Summary
### By Severity
- **Critical (2)**
  - Using an item you don't have / Out of range  
  - Negative text speed crashes the game  
- **High (2)**
  - Spamming input while text is displayed affects the next input checks  
- **Medium (1)**
  - Entering invalid inputs outside the range of valid inputs  
- **Low (3)**
  - High text speed makes dialogue slower  
  - Moon Blessing color changing  
  - Text speed setting not consistent  

**Total Bugs Filed:** 8  

### By Category
- Input Validation: 3  
- Logic Errors: 2  
- State Management: 0  
- UI/UX Issues: 2  
- Other: 0
  
## Test Environment
- Platform: Java Terminal  
- Game Version: 2/9/2026  
- Testing Tools: Manual testing + GitHub Issues  

## Conclusion
The game has **8 documented issues** ranging from critical to cosmetic. With focused effort on critical bugs, the core gameplay loop is playable. Input validation and text speed require the most attention.
________________________________________________________________________________________________________________________________________________________________________________
# Game Tested: Fshng
**Dev Team:** Evan Yango, Marcus Ceradini, Bianca Baccay, Ayah Abdalla, Maddy Puryear  
**QA Team:** Angel, Afton, Christopher, Marcus  
**Testing Period:** Week 2  
**Report Date:** 2/11/2026  

## Executive Summary
Over 2 days we conducted QA testing of *Fshng* and found **4 issues**.

**Key Finding:** The round does not start at 1 and there is no lose condition. Fish sometimes fly right when retrieving the rod.

## Coverage Summary
### Features Tested
- Casting rod: 100%  
- Fish catch amount: 70%  

### Testing Types
- Functional Testing  
- Negative Testing  
- Exploratory Testing
  
## Bug Summary
### By Severity
- **Low (4)**
  - Fish run off the screen  
  - Game does not start at round 1  
  - Unknown fish weight  
  - Weight of fish not indicated  

**Total Bugs Filed:** 4  

## Conclusion
Core gameplay functions work, but cosmetic issues and missing systems (shop, lose condition) need implementation.
________________________________________________________________________________________________________________________________________________________________________________
# Game Tested: Echo Of Terminal 7
**Dev Team:** Nayan, Khani Gauhar, Quint  
**Repo:** Q456lm/sprint1  
**QA Team:** Angel, Afton, Christopher, Marcus  
**Testing Period:** Week 2  
**Report Date:** 2/10/2026  

## Executive Summary
Found **4 issues**.

**Key Finding:** All puzzles but one do not function properly.

## Bug Summary

### By Severity
- **Critical (2)**
  - Admin puzzle does not accept correct password  
  - Power grid puzzle is impossible  
- **High (1)**
  - Bio-lab puzzle already completed  
- **Low (1)**
  - Two inputs needed to start the game  

**Total Bugs Filed:** 4  

## Conclusion
Core gameplay loop is **not playable** due to puzzle failures.
________________________________________________________________________________________________________________________________________________________________________________
# Game Tested: Black Jack
**Dev Team:** Samuel, Jessica, Karan, Maxwell  
**Repo:** mcnoffersinger/BlackJack  
**QA Team:** Angel, Afton, Christopher, Marcus  
**Testing Period:** Week 2  
**Report Date:** 2/11/2026  

## Executive Summary
Found **3 major issues**.

**Key Finding:** Most bugs stem from betting money you do not have.

## Bug Summary
### By Severity
- **High (2)**
  - Unlimited betting money  
  - Russian mode crashes game  
- **Low (1)**
  - Minus button adds to bet and Add button subtracts  

**Total Bugs Filed:** 3  

## Conclusion
Core gameplay works well. Infinite betting and Russian mode instability are top priority fixes.

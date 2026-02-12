STANDUP NOTES — Sprint pt.2 Day 1 (Feb 10th, Tuesday)

Attendance:
- Afton — ABSENT
- Chris — PRESENT  
- Angel — PRESENT  
- Marcus — PRESENT
  
Stand up:
Afton:
- What I did: Was not here
- What I’m doing: Accepting repo invention and help with the QA_TESTING_PLAN.txt file
- Blocked: not present

Christopher:
- What I did: Started testing for bugs in Echo of Terminal 7 and Christopher-Rise-Of-Mark-Ham games, and edited the QA_TESTING_PLAN.txt file in docs
- What I’m doing: Finishing testing the rest of the games and writing down the bugs
- Blocked: Hard to run the games, they are done with pygame

Angel:
- What I did: Edit STANDUP_NOTES.txt and QA_TESTING_PLAN.txt files and added them to GitHub
- What I’m doing: Making sure that the data we get is syntaxed correctly.
- Blocked: Hard to run the games, they are done with pygame

Marcus:
- What I did: Edit the QA_TESTING_PLAN.txt file and fixed its syntax in docs, and started testing for bugs in the fshng game
- What I’m doing: Finishing testing the rest of the games and writing down the bugs. Make sure that the data we get is syntaxed correctly.
- Blocked: Hard to run the games, they are done with pygame

Test Lead Notes: 
- Find 3 bugs per game, then go back and find more
- 14 bugs found total
- N/A: Not assigned
- Bugs found:
  - Christopher: The Rise of Mark-Ham
    - On the start menu, inputting a number that is not 1-2 jumps straight into the game, which is not intended. Invalid input check (Severity: Medium, Priority: )
    - If you spam input while text is being displayed, your input affects the next input checks. This stacks and can break the game (Severity: High, Priority: )
    - Setting text speed to a negative number and playing the game crashes it. No check/validation for negative speed (Severity: Critical, Priority: )
    - When in Menu, selecting 3 will return instead of going to the information codex (Severity: High, Priority: High)
    - When adjusting text speed, it is not consistent for all (Severity: Low, Priority: Low)
  - Echo of Terminal 7
    - In the power grid puzzle, you can’t select the green box. (Severity: N/A, Priority: N/A)
    - The bio-lab puzzle starts complete,d meaning you can't solve it. (Severity: N/A, Priority: N/A)
    - Inputting the correct password, “They are in the herd.” does not do anything, making the puzzle unsolvable (Severity: N/A, Priority: N/A)
  - Fshng
    - When booting the game, the round started at 2. Unintended behavior (Severity: N/A, Priority: N/A)
    - When surfacing with multiple fish, the rod and fish flew to the top right of the screen without user input. Unintended behavior (Severity: N/A, Priority: N/A)
    - Repeatedly catching no fish does not yield a loss. Unintended behavior (Severity: N/A, Priority: N/A)
  - Black Jack:
    - When you have no money, you can still bet. (Severity: N/A, Priority: N/A)
    - When you have no money, clicking the minus on the bet sets the bet to $10, thus increasing the bet. After this, clicking the plus button reverts the bet back to $0, thus decreasing the bet. (Severity: N/A, Priority: N/A)
    - Selecting Russian mode and spamming the hit or stand button causes the game to close. This soft-locks you. (Severity: N/A, Priority: N/A)

STANDUP NOTES — Sprint pt.2 Day 2 (Feb 11th, Wednesday)

Attendance:
- Afton — PRESENT(2nd Period)
- Chris — PRESENT  
- Angel — PRESENT  
- Marcus — PRESENT
  
Stand up:
Afton:
- What I did: Completed Christofer testing and summary report
- What I’m doing: Continue testing and writing summary report of Echo of Terminal 7
- Blocked: None

Christopher:
- What I did: Completed Christofer &testing and summary report 
- What I’m doing: Continue testing and writing summary report of Echo of Terminal 7
- Blocked: None

Angel:
- What I did: Finalize Fshng Plan & Summary Report with newly found bugs
- What I’m doing: Placing Summary reports into github
- Blocked: None

Marcus:
- What I did: Finalize Fshng Plan & Summary Report with newly found bugs. Added new bugs for Christofer and completed testing and some of summary report
- What I’m doing: Placing finalized content into github
- Blocked: None

Test Lead Notes: 
- 4 Bugs Total
- Bugs found:
  - Christopher: The Rise of Mark-Ham
    - After attempting to use moon blessing the actions are a darker shade of gray instead of the white it usually is.
    - When using an item if you input a number out of range for valid items it crashes
    - After setting text speed to a higher number like 200 dialogue becomes way slower
  - Fshng
    - We don’t know the weight of the fish so we cant make sure the pound are calculated correctly

STANDUP NOTES — Sprint pt.2 Day 3 (Feb 12th, Thursday)

Attendance:
- Afton — PRESENT
- Chris — PRESENT  
- Angel — PRESENT  
- Marcus — PRESENT
  
Stand up:
Afton:
- What I did: Completed Echo of Terminal 7 and Black Jack formatting of Testing and Summary Report
- What I’m doing: Black Jack testing and Summary
- Blocked: None

Christopher:
- What I did: Completed Echo of Terminal 7 and Black Jack formatting of Testing and Summary Report
- What I’m doing:  Black Jack testing and Summary
- Blocked: None

Angel:
- What I did: Completed formatting of summary report of every game and added to github
- What I’m doing: Continuing README File
- Blocked: None

Marcus:
- What I did: Completed formatting of testing plan of every game and updated standup notes(for the day). Added both to github
- What I’m doing: Stand up notes formatting
- Blocked: None

Test Lead Notes: 
- 0 Bugs Total
- Game bugs finalized 

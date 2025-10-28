## Project Overview

**System Under Test:** Word Puzzle Game Plus  
**Technology Stack:** HTML, CSS, JavaScript  
**Environment:** Chrome Browser (Desktop)

### Features Under Test

| Feature | Description | Risk Category |
|---------|-------------|---------------|
| Reset Game | Clears score and progress instantly | |
| Leaderboard | Stores top 3 scores in localStorage | |
| Bonus Round | Every 3 puzzles → doubles score | |

## Test Plan

### Objectives

- The goal of this test plan is to ensure that the word puzzle game works correctly, is easy to use and has no major bugs before release.

### Scope

**In Scope:**
- Game functionality (clicking, scoring, leaderboard auto-update scores in descending order)
-	User interface (buttons, text, layout)
-	Saving and loading scores
-	Performance (no crashes)


**Out of Scope:**
- Mobile version

### Tools & Resources

- Test strategy
    1.	Functional testing – check if all features work as expected.
    2.	UI testing – make sure the design looks good and buttons work
    3.	Save/load testing – verify that progress is saved correctly  
- Test environment
    Browser: chrome
- Device: 
    laptop


### Schedule

| Phase | Planned Duration | Actual Duration | Status |
|-------|------------------|-----------------|--------|
|1. Write test cases |24 hours |24 hours |Done |
|2. Execute tests |24 hours |48 hours |Ongoing |
|3. Fix & retest bugs | 24 hours| - |Ongoing |
|4. Final review |3 hours |1 hour |Done |

## Risk Analysis

### Risks

| ID | Feature | Risk Description | Likelihood | Impact | Priority | Mitigation Strategy |
|----|---------|------------------|------------|--------|----------|---------------------|
| | | | | | | |



-----------------------------
### **Test Cases**

**Test Case**| **Description**| **Expected**|**Actual**|**Pass/Fail**|
|-------|-------|--------|-------|------
1.Browser Compatibity| To test whether the app works well in different brosers eg. Internet Explorer, Firefox etc.| The app should work across all the brosers | It does work well in some brosers eg. Mozilla Firefox| Fail|
|2.Update of leaderboard|The updateLeaderbord should update the leaderboard after the game is reset|The leaderboard should be updated correctly|The leaderboard is updated while the game is still on- before reset-|Fail|
|3.Device Compatibility|Aims at testing whether the app is compatibible with aother devices eg Androids, Apple phones, tablets|The app should work across other devices eg. Android phones, Apple Phones, tablets etc|The device works well across a number of devices which is good|Pass|
|4.Showing Hint|To test whether the hint reduces the score by 2 when it is used|The current score should be reduced by 2 when the hint is used|Using hint  reduces score by 2 points|Pass|
|5.Scoreboard calculation|To test whether the score board is calculated correctly as the user gain more points|It should update the scores as the user plays|Scoreboard is updated successfully|Pass|
|6.Reset game|Reset clears score & progress (leaderboard remains)|Should reset the scores and progress|Reset works successfully|Pass|
|7.Guess validation|Test whether the a user can submit blank values |invalid input|Invalid input|Pass|


### **2. Flow Testing**

**Objective:** Identify major UI states and test how the system transitions between them.  

### **4.1 States Identified**
- Start / Idle  
- InputReady
- Hint/ Submit / NewPuzzle 
- Results  
- NoResults  
- Reset / Clear  

### **4.2 Actions and Transitions**

| Current State | Action / Event | Expected Next State | Actual Next State | Pass/Fail |
|----------------|----------------|---------------------|-------------------|-----------|
|Start|Hint| Displays hint| Displays hint|Pass|
|InputReady| Submit| Results|Results|Pass|
| InputReady| New Puzzle|Displays a different puzzle|Displays a different puzzle| Pass|
|Input Ready| Reset| No results| No Results|Pass|
|start| Submit| No Results| No results|Pass|


### **3.Issues Identified**

| Issue Type            | Description                                                                 |
|-----------------------|-----------------------------------------------------------------------------|
| Manual Code Review    |Perfomance concern|
| SonarQube Analysis             | Intentionality issue, Consistency issue  |


![alt text](<Screenshot (35).png>)
![alt text](<Screenshot (41).png>)
![alt text](<Screenshot (42).png>)

## Defects

| ID | Issue Title | Severity | Risk ID | Status | GitHub Link |
|----|-------------|----------|---------|--------|-------------|
| | | | | | |

## Metrics

- Test Case Pass Percent: 
- Defect Density: 
- Risk Coverage Percent: 
- Regression Success Rate: 

### Defect Summary

- Total Defects Logged: 
- Critical High: 
- Fix Rate: 

## Test Control & Project Management

### Phases

| Phase | Deliverable | Actual Output | Variance | Owner |
|-------|-------------|---------------|----------|-------|
| 1| Test schedule | test schedule | | Mercy Benu |
| 2| Test cases | Test cases | | Markpaul Ndirangu |
| 3| Test report |test report | |  Viron Ochieng' |
| 4| Final report | final report | | All |

**Progress Tracking Method:**  
**Change Control Notes:**

## Lessons Learned

- Most Defect Prone Feature: 
- Risk Analysis Impact: 
- Team Communication Effectiveness: 
- Improvements for Next Cycle: 

## Attachments

- 

## Sign Off

| Name | Role | Initials | Date |
|------|------|-----------|------|
| Mercy Benu | Test Manager | mb | 27th October 25|
| Markpaul Ndirangu | Risk Analyst | mn | 27th October 25|
| Viron Ochieng' | Test Executor | vo | 27th October 25|


## Overall Summary

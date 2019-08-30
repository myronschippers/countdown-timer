# Countdown Timer

This is an exercise meant to be completed using a front-end framework of your choosing and state management of some kind. THe sample solution will be built out with React and Redux but there are a few other options listed below. 

## The Scenario

We have an event where **Participants** are supposed to complete a task in isolation from one another but they are given a fixed amount of time in order to complete the task. Our **Event Coordinator** is supposed to monitor the **Participants** and ensure that they are not going over time. The **Participant** should also be able to see their individual countdown without seeing anyone elses. In the **Event Coordinator's** view they should have a timer value that they can set and then be able to kick off all of the **Participant's** countdown timer at the same time. There will be cases where the **Coordinator** will need to start an individual **Participant's** timer without the rest of the group.

### Requirements

**Master Timer Form:**
- [ ] We need 3 inputs for hours, minutes, and seconds.
    * Each input should only allow whole numbers (integers) and should not allow a value less than 0
    * Hours field should allow a max value of 12
    * Minutes field should allow a max value of 59
    * Seconds field should allow a max value of 59
- [ ] A **Start All Clocks** button should be available just below the form fields and when clicked it should kick off the countdown timer for all of the clocks.
- [ ] A **Reset All Clocks** button should be display below the form fields just to the right of the *Start All Clocks* button and when clicked should return all clocks to the time that was entered in the fields originally.
- [ ] A **Stop All Clocks** button should be displayed below the form fields just to the right of the *Reset All Clocks* button and when clicked it should pause all of the **Participant** clocks at the same time.
- [ ] A **Clear All Clocks** button should be displayed below the time form fields just to the right of the *Stop All Clocks* button and when clicked it should clear out the time form fields and reset all the clocks to zero.

**List of Clocks:**
- [ ] At least 2 individual clocks should be displayed on the page and no less than 2 allowed
- [ ] There should be an **Add Clock** button displayed above the clocks and when clicked a new clock should be added to the list of clocks visible on the page

**Individual Clocks:**
- [ ] Digital heads-up clock display is show and when countdown is started the clock display will show the countdown in real-time
- [ ] **Delete** button will be available to remove one of the clocks from the list
- [ ] **Start** button that when clicked will start the countdown timer for the individual clock only and while the countdown timer is active the button should be disabled
- [ ] **Pause** button when clicked should stop only the individual clock's countdown timer
- [ ] **Reset** button when clicked stops the current countdown timer then sets the time to the original entered value
- [ ] **Clear** button when clicked will stop the countdown timer and then set the time to 00:00:00

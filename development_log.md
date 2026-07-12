# GlowTrack Development Log

## May 30, 2026

### Features Added
- Mood tracking system
- Personalized mood responses
- Random affirmation generator
- Habit tracker
- Habit completion counter

### Challenges Encountered
- Multiple indentation errors
- Variable scope issue with `answer`
- Learning how loop indentation affects program flow
- Forgot to save README before committing 😭

### What I Learned
- How `for` loops process lists
- How counters work using `+= 1`
- How program flow changes based on indentation
- How to use `random.choice()` with lists
- The importance of saving files before committing to Git

### Next Planned Features
- Refactor code into functions
- Water intake tracking
- Journaling section
- Data saving with CSV or JSON

## May 31, 2026

### Refactoring Improvements

- Created log_mood() function
- Created track_habits() function
- Created show_affirmation() function
- Simplified main() into a menu controller

### What I Learned

- Functions help organize large programs
- Each function should have a single responsibility
- Refactoring improves readability without changing functionality
- Clean code is easier to maintain and expand

# GlowTrack Development Log

## Version 0.3

### Feature Added
- Implemented a repeating main menu using a `while` loop.
- The application now stays open after completing an action and only exits when the user selects "Exit."

### Why This Matters
Previously, GlowTrack closed after completing a single task. The new menu system creates a smoother user experience and makes the application behave more like a real program.

### Challenges
- Learned how to use a `while True` loop.
- Used the `break` statement to exit the program cleanly.
- Tested each menu option to ensure it returned to the main menu correctly.

### What I Learned
- How `while` loops can keep a program running.
- When to use `break` to stop a loop.
- How to improve the overall user experience with better program flow.

### Next Goals
- Add a water intake tracker.
- Add a journaling feature.
- Begin saving user data to JSON files.

## July 12, 2026

## Version 0.4 – Water Tracker

### Feature Added
- Added a daily water intake tracker.
- Set a default daily hydration goal of 64 ounces.
- Allowed users to enter the number of ounces consumed.
- Calculated the current total and remaining ounces.
- Added progress-based encouragement messages.
- Prevented remaining ounces from displaying as a negative number after the goal is reached.

### Challenges
- Converting user input from text into an integer.
- Deciding where the progress conditions should be placed.
- Handling totals that exceeded the daily goal.
- Removing duplicated menu code that affected program flow.

### What I Learned
- How to convert user input using `int()`.
- How to update a numeric total with `+=`.
- How to calculate remaining progress using subtraction.
- How to use `if`, `elif`, and `else` with numeric values.
- How to adjust calculated values to improve the user experience.
- How to debug duplicated code and indentation problems.

### Next Goals
- Add a journaling feature.
- Add better input validation.
- Save wellness data using JSON.
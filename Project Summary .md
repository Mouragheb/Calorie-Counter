# Calories Counter JS

A Pen created on CodePen.io. Original URL: [https://codepen.io/Mouragheb/pen/KKOYYXy](https://codepen.io/Mouragheb/pen/KKOYYXy).

This code implements a calorie counter web application that allows users to input their daily calorie budget, record their calorie intake for meals and snacks, account for exercise calories burned, and calculate their remaining calorie balance. The user interface is built using HTML, styled with CSS, and functionality is added through JavaScript. Below is an explanation of each section:
Languages Used
1. HTML: Creates the structure and elements of the webpage.
2. CSS: Styles the elements for better presentation and responsiveness.
3. JavaScript: Adds interactivity, handles calculations, and dynamically updates the webpage.
Code Functionality
HTML (Structure)
1. Form Elements:
• A form titled “Calorie Counter” contains input fields for:
• Daily calorie budget.
• Entries for breakfast, lunch, dinner, snacks, and exercise.
• Each section (e.g., breakfast, lunch) can have multiple entries added dynamically.
2. Controls:
• Dropdown to select a section (e.g., breakfast, lunch).
• Button to add new food or exercise entries.
• Buttons to calculate remaining calories or clear the form.
3. Output:
• A section displays the calorie balance after calculation, indicating whether the user is in a “Deficit” (under budget) or “Surplus” (over budget).
CSS (Styles)
1. Styling Variables:
• Uses CSS variables for consistent colors across the app (e.g., –light-yellow for buttons, –light-pink for surplus).
2. Responsive Design:
• The container adjusts its width for smaller screens.
3. Visual Enhancements:
• Buttons, inputs, and fieldsets have consistent spacing and alignment.
• The output section is styled to display clear results with a color-coded surplus or deficit.
JavaScript (Interactivity)
1. Dynamic Entry Addition:
• Clicking the “Add Entry” button dynamically adds input fields for the selected category (e.g., breakfast or exercise).
2. Calorie Calculation:
• Calculates the sum of calories consumed (breakfast, lunch, dinner, snacks).
• Subtracts these from the calorie budget.
• Adds exercise calories burned to the budget.
• Displays the balance as a surplus or deficit.
3. Input Validation:
• Sanitizes inputs to remove unwanted characters (e.g., spaces, signs).
• Checks for invalid inputs (e.g., scientific notation).
4. Form Clearing:
• Clears all input fields and results when the “Clear” button is pressed.
5. Event Listeners:
• addEntryButton for adding dynamic inputs.
• calorieCounter form submission for calculations.
• clearButton for resetting the form.
How It Works
1. Set a Calorie Budget:
• Input a daily calorie goal.
2. Add Entries:
• Use the dropdown to select a category (e.g., breakfast).
• Click “Add Entry” to add food or exercise entries with their calorie amounts.
3. Calculate Remaining Calories:
• Click the “Calculate Remaining Calories” button to see the calorie balance.
4. Clear the Form:
• Click the “Clear” button to reset everything.
Output Example
• Input:
• Budget: 2000 calories.
• Breakfast: 300 calories.
• Lunch: 500 calories.
• Dinner: 700 calories.
• Exercise: 200 calories burned.
• Output:
• Remaining Calories: 200 Calorie Deficit
• Breakdown:
• Budget: 2000
• Consumed: 1500
• Burned: 200
This is a basic calorie tracking app designed for educational purposes, but it demonstrates how HTML, CSS, and JavaScript work together to create interactive web applications.

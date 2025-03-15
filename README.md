# Calorie-Counter
You can access the counter in this link below:
https://fadliazharr.github.io/Calorie-Counter/
  

A simple web-based **Calorie Counter** that helps users track their daily calorie intake and burned calories. It allows users to input meals and exercises, then calculates whether they are within their set calorie budget.  

---

## Features  

- Set a **daily calorie budget**  
- Add food entries for **Breakfast, Lunch, Dinner, and Snacks**  
- Add **Exercise** to track burned calories  
- **Calculate** remaining calories dynamically  
- **Clear** all inputs with a reset button  
- Shows if you're in a **calorie deficit or surplus**  

---

## How It Works  

1. **Set Your Daily Calorie Budget**  
   - Enter your target daily calorie limit in the **Budget** input field.  

2. **Add Meals & Exercise Entries**  
   - Choose a category (Breakfast, Lunch, Dinner, Snacks, or Exercise) from the dropdown.  
   - Click **"Add Entry"** to add a new input field for that category.  
   - Enter the **name** and **calories** for each food item or exercise.  

3. **Calculate Your Remaining Calories**  
   - Click **"Calculate Remaining Calories"** to see the results.  
   - The app will show:  
     - Calories **Budgeted**  
     - Calories **Consumed**  
     - Calories **Burned**  
     - Your **remaining calories** (highlighted in green for a deficit, red for a surplus).  

4. **Clear Everything**  
   - Click the **"Clear"** button to reset all fields and start over.  

---

## Technologies Used  

- **HTML** – Structure of the app  
- **CSS** – Styling and layout  
- **JavaScript** – Core functionality  

---

## Code Overview  

### **HTML (`index.html`)**  
- Creates the structure of the calorie counter.  
- Contains form inputs for calorie tracking.  
- Uses **fieldsets** to categorize meals and exercise.  

### **CSS (`styles.css`)**  
- Defines a clean and minimal UI.  
- Uses color coding for calorie results (green for deficit, red for surplus).  
- Applies modern styling with **flexbox** and variables.  

### **JavaScript (`script.js`)**  
- Handles adding new input fields dynamically.  
- Calculates **total consumed & burned calories**.  
- Prevents invalid inputs (like scientific notation).  
- Displays results dynamically in the **output section**.  

---

## Expected Output  

After entering a **calorie budget**, adding meals, and logging exercises, the app will display:  

✅ **500 Calorie Deficit** *(if under budget)*  
❌ **200 Calorie Surplus** *(if over budget)*  

Along with:  
- **Total Calories Budgeted**  
- **Total Calories Consumed**  
- **Total Calories Burned**  

---


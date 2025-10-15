Hearthstone Combo Calculator

Overview

This is a web-based calculator for determining the optimal damage output of the Wilted Shadow + Bandages combo in Hearthstone. It calculates the total damage dealt to an enemy based on Wilted Shadow's attack values, the number of Bandages, Hero Power (Lesser Heal), and the enemy's health and armor. The tool also provides a detailed event log and a history of calculations.

Features





Input Fields:





Wilted Shadow attack values (comma-separated for multiple minions).



Number of Bandages (Heal 3).



Option to use Hero Power (Lesser Heal - Heal 2).



Enemy's maximum health, current health, and armor.



Calculation:





Computes total damage and determines if the enemy is defeated (lethal).



Suggests optimal Hero Power usage order for maximum damage.



Displays unused Bandages if lethal is achieved early.



History Table:





Displays calculation history in a vertical table format with a scrollbar for overflow.



Columns include attack values, Bandages used, Hero Power usage, initial health/armor, actual Bandages used, enemy status, and final health/armor.



Includes a "Delete" button for each calculation entry.



Responsive Design:





Adapts to mobile and desktop screens.



Styled with a Hearthstone-themed background and card images.

Installation





Clone or download the repository.



Open index.html in a web browser.



No additional dependencies are required as all resources (images, styles, scripts) are embedded or linked via CDN.

Usage





Enter Wilted Shadow attack values (e.g., 6 or 7, 7, 9).



Specify the number of Bandages.



Check the Hero Power box if you want to include Lesser Heal.



Input the enemy's maximum health, current health, and armor.



Click คำนวณความเสียหายคอมโบ to compute the damage.



View results, including:





Enemy status (lethal or alive).



Final health and armor.



Optimal Hero Power usage (if applicable).



Detailed event log (toggleable).



History table updates automatically and persists across sessions using localStorage.



Delete specific history entries by clicking the "ลบ" button in the history table.



Click รีเซ็ตค่าเริ่มต้น to clear inputs and results (history remains unless deleted).

Notes





The history section is always visible unless no calculations have been performed.



The calculator assumes valid inputs (positive numbers, current health ≤ max health).



Error messages display for invalid inputs.



The event log provides a step-by-step breakdown of the combo sequence.

Technologies Used





HTML/CSS/JavaScript: Core web technologies for structure, styling, and logic.



LocalStorage: For persisting calculation history.



Hearthstone Wiki Images: Card images for visual appeal.

License

This project is for personal use and not licensed for commercial distribution. Hearthstone and related assets are property of Blizzard Entertainment.

# Frontline EXP Calculator

## **Overview**  
This Python script calculates the number of PvP matches needed to reach a target PvP level in *Final Fantasy XIV: Dawntrail (Patch 7.1 and hopefully onwards)*. It considers all of the current game modes; **Frontline**, **Rival Wings**, and **Crystalline Conflict**, factoring in win/loss experience values.

## **How It Works**  
1. **User Input:**  
   - Current PvP level (max 39).  
   - Target PvP level (max 40).  
   - Current experience points towards the next level (max 19,999).  

2. **EXP Calculation:**  
   - Retrieves required EXP for each level from a predefined list.  
   - Computes remaining EXP needed to reach the target level.  

3. **Match Requirement Calculation:**  
   - Determines the number of matches needed for each mode based on win/loss experience values.  

4. **Results Display:**  
   - Outputs the required number of wins/losses in different PvP modes to reach the target level.  

## **Usage**  
Run the script in a Python environment, enter the requested values, and view the results showing how many matches are needed to level up.

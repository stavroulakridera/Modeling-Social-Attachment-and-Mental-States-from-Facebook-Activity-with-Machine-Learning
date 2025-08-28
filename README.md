# Modeling-Social-Attachment-and-Mental-States-from-Facebook-Activity-with-Machine-Learning

# Attachment Strength (Second Paper)

This repository was created as part of the **second paper**.  
It includes my own implementations of the attachment strength formulas (original and revised), following the methodology presented in the first project **team2-ethi-mental-state**.

## Contents
- `data/table2_50.csv` — Dataset with 50 users in the format of Table 2 (Normalized Scoring Function).  
- `data/table3_50.csv` — Dataset with 50 users in the format of Table 3 (Weighted Linear Combination).  
- `tie_strength.py` — Python code with functions implementing the two formulas.

## Formulas

1. **Attachment Strength (original):**  
   	-0.76 × (Days since last communication)  
   	+ 0.111 × (Words expressing intimacy)  
   	+ 0.135 × (Degree of positive emotions)  
   	+ 0.299 × (Wall posts)  
   	+ 0.299 × (Messages)  
   	+ 0.299 × (Comments)

2. **Attachment Strength (revised):**  
   	-0.85 × (Days since last communication)  
   	+ 0.25 × (Words expressing intimacy)  
   	+ 0.25 × (Degree of positive emotions)  
   	+ 0.27 × (Wall posts)  
   	+ 0.27 × (Messages)  
   	+ 0.27 × (Comments)

## Notes
- Rows ID1–ID10 in both datasets replicate the paper exactly.  
- Rows ID1–ID50 are synthetic but consistent with the same ranges.  
- This work extends the original repository **team2-ethi-mental-state** with customized data and formulas for publication purposes.

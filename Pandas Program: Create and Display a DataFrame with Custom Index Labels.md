# Pandas Program: Create and Display a DataFrame with Custom Index Labels

## 🎯 Aim

To create and display a **DataFrame** using the **Pandas** library in Python from a given dictionary, and apply specific index labels to the rows.

---

## 🧠 Algorithm

1. **Import Libraries**: Import the required libraries – `pandas` and `numpy`.
2. **Create Dictionary**: Define a dictionary `exam_data` with keys: `'name'`, `'score'`, `'attempts'`, and `'qualify'`.
3. **Index Labels**: Create a list of custom index labels called `labels`.
4. **Create DataFrame**: Use `pd.DataFrame()` to create the DataFrame by passing the dictionary and index labels.
5. **Display Output**: Display the DataFrame using `print()` or by simply calling the DataFrame variable.

---

## 💻 Program
```
import numpy as np
import pandas as pd
a=eval(input())
b=np.array(eval(input()))
df=pd.DataFrame(a,index=b)
print(df)
```
## Output
<img width="949" height="241" alt="Screenshot 2025-10-21 191043" src="https://github.com/user-attachments/assets/7f70f48b-8b00-443c-a98d-ae7f0e2b17d7" />

## Result
Thus,the python program To create and display a DataFrame using the Pandas library in Python from a given dictionary, and apply specific index labels to the rows is created successfully.

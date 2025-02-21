# Secret Constant Solver  

This project reads JSON files containing encoded numerical data, extracts key values, and applies Lagrange Interpolation to determine a secret constant.  

## How It Works  
- Reads input data from JSON files (`input1.json`, `input2.json`).  
- Extracts `n` (number of points) and `k` (points to use for interpolation).  
- Converts values from different bases and stores them as coordinate points.  
- Uses Lagrange Interpolation to determine the hidden constant `c`.  

## Prerequisites  
- Node.js installed on your system  

## How to Run  
1. Clone the repository:  
   ```
   git clone <repository_url>
   cd <repository_name>
   ```  
2. Place your JSON files (`input1.json`, `input2.json`) in the project directory.  
3. Run the script:  
   ```
   node solution.js
   ```  

## Example Output  
```
Processing Test Case 1...
n: 5 k: 3
Extracted Points: [[1, 10], [2, 20], [3, 30], [4, 40], [5, 50]]
Using first 3 points for interpolation: [[1, 10], [2, 20], [3, 30]]
Secret constant c: 0
```

## Acknowledgments  
This project was developed with guidance from GPT, which provided insights into debugging, improving efficiency, and structuring the logic for interpolation. 🚀  

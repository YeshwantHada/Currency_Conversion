#**Currency Conversion to USD**
## **Overview**
This project fetches real-time currency conversion rates against the **US Dollar (USD)** using the https://fixer.io/ and exports the data into an **Excel file** for easy access and analysis.

---

## **Features**
✔ Fetch latest currency exchange rates from Fixer.io  
✔ Convert all currencies relative to USD  
✔ Save results in an Excel file with a timestamp  

---

## **Requirements**
Install dependencies:
```bash
pip install -r requirements.txt
```

`requirements.txt`:
```
requests
pandas
openpyxl
```

---

## **Usage**
1. Get your API key from https://fixer.io/.
2. Replace `YOUR_ACCESS_KEY` in the script.
3. Run the script:
```bash
python src/currency_to_excel.py
```

---

## **Output**
The script creates an Excel file named `currency_rates.xlsx` with the following columns:
- **Currency**: Currency code (e.g., EUR, INR)
- **Rate**: Conversion rate against USD
- **Timestamp**: When the data was fetched

**Example Output:**
| Currency | Rate     | Timestamp           |
|----------|----------|----------------------|
| EUR      | 0.92     | 2025-11-07 15:21:00 |
| INR      | 83.10    | 2025-11-07 15:21:00 |

---

## **License**
This project is licensed under the MIT License.

---

## **Contributing**
Feel free to fork this repository, submit issues, and create pull requests. Contributions are welcome!

---

## **Author**
**Yeshwant Hada**  
https://github.com/YeshwantHada

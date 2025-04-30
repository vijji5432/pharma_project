
However, due to a **400 Client Error (BadRequest)** when attempting direct access to this API endpoint, the data was instead retrieved programmatically using the `pubchempy` Python library.

---

## 🧰 Libraries Used

- `pandas`
- `matplotlib`
- `seaborn`
- `pubchempy`

---

## 🧬 Compounds Analyzed (by CID)

- **2244** - Aspirin  
- **1983** - Paracetamol  
- **702**  - Ethanol  
- **6322** - Guanidine Acetate  
- **5957** - ATP (Adenosine Triphosphate)

---

## 🧼 Steps Performed

1. **Data Retrieval**  
   Used `pubchempy` to fetch properties like Molecular Weight, LogP, InChIKey, and Canonical SMILES.

2. **Data Inspection**  
   - Verified column names and data types.  
   - Confirmed there were no missing values.  

3. **Data Cleaning**  
   - No cleaning required as all data fields were complete.

4. **Visualization**  
   - **Scatter Plot**: Molecular Weight vs LogP  
   - **Bar Plot**: LogP vs Compound CID

5. **Bonus Insight**  
   - **LogP (Partition Coefficient)** helps determine **solvent selection** in drug development:
     - Negative LogP ➝ polar solvents (hydrophilic)
     - Positive LogP ➝ non-polar solvents (lipophilic)

---

## 📊 Visual Outputs

- `Molecular Weight vs LogP`: Highlights the correlation between molecular size and hydrophobicity.
- `LogP vs Compound`: Comparison of lipophilicity across compounds.

---

## ✅ Results Summary

- Data successfully retrieved and visualized.
- No missing data detected.
- Trends observed in LogP values help assess solvent compatibility.


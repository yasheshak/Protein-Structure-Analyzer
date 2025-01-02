# **Protein Structure Analysis Tool**

## **Overview**
This tool allows you to analyze protein structures retrieved from the RCSB Protein Data Bank (PDB). It calculates and visualizes the surface area and secondary structure of proteins using **BioPython**. The tool supports batch processing of multiple proteins by their PDB IDs.

---

## **Features**
1. **Fetch and Parse PDB Files**:
   - Downloads PDB files using their unique 4-character identifier (e.g., `1B3K`).
   - Parses the structure for further analysis.

2. **Surface Area Calculation**:
   - Computes the solvent-accessible surface area (SASA) of proteins using the Shrake-Rupley algorithm.

3. **Secondary Structure Analysis**:
   - Identifies secondary structure elements (e.g., helices, strands) using DSSP.
   - Visualizes the frequency of secondary structure types.

4. **Visualization**:
   - Bar charts for protein surface area comparison.
   - Secondary structure frequency charts for individual proteins.

---

## **Dependencies**
- **Python 3.x**
- **BioPython** (`pip install biopython`)
- **Matplotlib** (`pip install matplotlib`)

---

## **Usage**
1. **Input**:
   - Provide one or more PDB IDs as input, separated by commas.
   - Example: `1B3K, 1BML, 1C4P`

2. **Execution**:
   Run the script in a Python environment:
   ```bash
   python script_name.py

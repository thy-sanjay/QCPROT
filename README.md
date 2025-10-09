<img width="192" height="192" alt="icon" src="https://github.com/user-attachments/assets/61b5ec96-b47f-4ea3-9e74-53a57027a3c1" />

# QCPROT: Quality Check for Proteomics Data

**QCPROT (Quality Check for Proteomics Data)** is an open-source Python framework built to perform automated quality check on RAW Proteomics Data dervied as mzML.

---

It performs comprehensive data evaluation through statistical summaries, visualization driven insights, and automated PDF report generation, ensuring quality check proteomics datasets for downstream analysis.

---

## Features

- **Automated QC Report Generation:** End-to-end PDF report summarizing all quality metrics and visualizations.  
- **Raw Data Quality Assessment:** Extracts and analyzes mzML-derived metrics to ensure instrument and acquisition reliability.  
- **Dynamic Plot Generation:** Produces a variety of QC plots for individual samples and combined datasets.  
- **Reproducible Workflow:** Designed to integrate seamlessly with existing proteomics pipelines.  
- **Lightweight & Modular:** Minimal dependencies, easy to extend and customize for specific experimental setups.

---

## Core Functionalities

| Category | Function | Description |
|-----------|-----------|-------------|
| **Data Processing** | mzML Parsing | Reads and processes mzML files for QC metric extraction |
| **Computation** | Statistical Analysis | Calculates various QC metrics like intensity distributions, TIC, MS/MS counts, etc. |
| **Visualization** | Plot Generation | Automatically generates individual and combined QC plots |
| **Reporting** | PDF Summary | Compiles all QC plots and metrics into a single PDF report |
| **Automation** | Batch Processing | Handles multiple samples for scalable QC analysis |

---

## Why QCPROT?

High-throughput proteomics experiments often generate large volumes of spectral data where quality issues can easily go unnoticed.  
QCPROT streamlines this verification process by automatically diagnosing potential issues such as:
- Inconsistent MS/MS acquisition rates  
- Signal intensity deviations  
- Poor ionization or detector instability  
- Run-to-run variability  

By integrating QCPROT early in the data processing pipeline, researchers can ensure only high-quality spectra proceed to downstream quantification and identification.

---

## Author

**Developed by:** Sanjay S  
**Contact:** thy.sanjay@gmail.com

---

## License

Released under the **MIT License**.  
You are free to use, modify, and distribute this software with proper attribution.

---

## Citation / Acknowledgment

If you use **QCPROT** in your work, please cite or acknowledge:  
> *Sanjay S. (2025). QCPROT: Quality Check for Proteomics Data. GitHub Repository.*

---

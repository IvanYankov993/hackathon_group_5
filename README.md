# Nanopore: Defect Detection in Graphene Sheets

## Group 5 - AI4SD Machine Learning Summer School Project

**Authors:**  
Bachs Herra, Anna, Cisse, Aboulatif, de la Cruz Nunez Andrade, Emilio Alexis, Deussen, Philipp, Yankov, Ivan, Frey, Jeremy G., Niranjan, Mahesan, and Kanza, Samantha.

**Publication:**  
Bachs Herra et al. (2022). Group 5: Challenge: Nanopore "Defect Detection in Graphene Sheets" (AI4SD-Machine-Learning-Summer-School, 3). University of Southampton. DOI: [10.5258/SOTON/AI3SD0246](https://doi.org/10.5258/SOTON/AI3SD0246).

---

## 📝 Project Overview

### **Abstract**
Graphene is a nanomaterial known for its exceptional properties, including:
- **High electrical conductivity**
- **Mechanical strength**
- **Impermeability to gases**  

Its applications include:
- *Electronic and optoelectronic devices*  
- *Gas sensors* (e.g., chemiresistors for ammonium and nitrogen dioxide detection)  
- *Biosensors and energy storage devices*  

### **Defect Detection Challenge**
The goal of this project was to develop a classifier to detect defects in graphene sheets using **Surface Scanning Electron Microscopy (SEM)** images.  

**Dataset Details**:
- **180 SEM images** (256x256 pixels, full-stack).  
- **2279 images** (48x48 pixels) of *perfect patches (pp)*.  
- **32 images** (48x48 pixels) of *defect-containing patches (dp)*.  

> *Note*: All pixel values were normalized between `0.00` and `1.00`.  

---

## 📂 Dataset

**Dataset Structure:**

data |-- full_stack/ # 256x256 SEM images |-- perfect_patches/ # 48x48 images without defects |-- defect_patches/ # 48x48 images with defects


---

## ⚙️ Methodology
The project required the design of a machine learning classifier capable of distinguishing between perfect and defect-containing graphene patches. Evaluation metrics and performance results were documented in the study.

---

## 🛠️ License

This work is licensed under the **Creative Commons Attribution License**.

---

## 📅 Additional Information

- **Published Date:** July 8, 2022  
- **Event:** AI4SD Machine Learning Summer School, University of Southampton (June 20–24, 2022)  
- **Keywords:** *AI3SD, Machine Learning, Graphene Defect Detection, SEM Images*  

---

## 📖 Citation

@misc{nanopore_defects_2022, title={Nanopore: Defect Detection in Graphene Sheets}, author={Bachs Herra, Anna and Cisse, Aboulatif and de la Cruz Nunez Andrade, Emilio Alexis and Deussen, Philipp and Yankov, Ivan and Frey, Jeremy G. and Niranjan, Mahesan and Kanza, Samantha}, year={2022}, url={https://doi.org/10.5258/SOTON/AI3SD0246}, institution={University of Southampton} }

yaml
Copy code

---

## 📧 Contact
For any questions or inquiries, please contact the authors or visit the [AI3SD Machine Learning 

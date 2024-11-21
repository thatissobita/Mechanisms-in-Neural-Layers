# Mechanisms for Neural Layers  

Welcome to the **Mechanisms for Neural Layers** repository! This project explores advanced neural mechanisms designed to enhance the learning and plasticity of spiking neural networks. By implementing lateral inhibition, K-Winners-Take-All (KWTA) competition, and homeostasis mechanisms, this repository demonstrates how networks can achieve better and faster learning while maintaining stability.  

---

## Features  

- **Lateral inhibition:**  
  - Implements inhibitory interactions between neurons to enhance contrast and improve learning dynamics.  

- **K-Winners-Take-All (KWTA):**  
  - Models a competitive mechanism where the top K neurons are selected to remain active, promoting sparsity and efficient representation.  

- **Homeostasis:**  
  - Introduces mechanisms to regulate the firing rates of neurons and maintain network stability over time.  

- **Interactive notebook:** A single Jupyter notebook (`Mechanisms-for-Neural-Layers.ipynb`) consolidates all implementations and analysis.  

- **Visualization resources:** Pre-generated plots and figures included in the `resources/` folder.  

- **Detailed report:** A comprehensive `report.pdf` providing theoretical background, results, and insights.  

---

## Installation  

1. Clone this repository:  
   ```bash  
   git clone https://github.com/yourusername/Mechanisms-for-Neural-Layers.git  
   cd Mechanisms-for-Neural-Layers  
   ```  

2. Install dependencies:  
   ```bash  
   pip install -r requirements.txt  
   ```  

   **Note:** Ensure you have Python 3.8 or higher installed.  

---

## Usage  

### Running the Jupyter Notebook  

1. Open the Jupyter notebook:  
   ```bash  
   jupyter notebook Mechanisms-for-Neural-Layers.ipynb  
   ```  

2. Follow the step-by-step implementation of lateral inhibition, KWTA, and homeostasis mechanisms.  
3. Visualize results and analyze how these mechanisms affect learning and plasticity.  

---

## Directory Structure  

```plaintext  
Mechanisms-for-Neural-Layers/  
│  
├── Mechanisms-for-Neural-Layers.ipynb  # Jupyter notebook containing all implementations and analysis  
│  
├── report.pdf                          # Detailed report including results and analysis  
│  
├── resources/                          # Folder for visualization resources  
│   ├── lateral_inhibition              # Visualization of lateral inhibition  
│   ├── kwta_mechanism                  # Visualization of KWTA mechanism  
│   ├── homeostasis_dynamics            # Visualization of homeostasis dynamics  
│  
├── requirements.txt                    # Python dependencies  
├── LICENSE                             # License information  
├── README.md                           # Project documentation  
└── .gitignore                          # Git ignored files  
```  

---

## Results  

The `resources/` folder contains pre-generated plots and visualizations, including:  
- Activity patterns with lateral inhibition.  
- Competitive dynamics from KWTA.  
- Firing rate regulation with homeostasis.  
- Improved learning curves with enhanced mechanisms.  

Refer to the `report.pdf` for a detailed discussion of these results.  

---

## Dependencies  

- Python 3.8+  
- `pymonntorch`
- `pytorch` 
- `numpy`  
- `matplotlib`  

Install all dependencies using the provided `requirements.txt` file.  

---

## Contributing  

Contributions are welcome! To contribute:  
1. Fork the repository.  
2. Create a feature branch.  
3. Submit a pull request with your changes.  

For major changes, please open an issue to discuss your ideas.  

---

## Acknowledgements  

This project leverages the [pymonntorch](https://github.com/pymonntorch/pymonntorch) framework for spiking neural network simulations.  

Happy experimenting with neural mechanisms for enhanced learning and plasticity!

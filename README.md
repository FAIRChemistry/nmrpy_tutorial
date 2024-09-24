# NMRpy Tutorial
## 5th EnzymeML Workshop

Welcome! This is the tutorial for the 5th EnzymeML Workshop. In this tutorial, we will learn how to use the NMRpy library to process and analyze NMR data. The tutorial is divided into the following sections:

1. Creating the EnzymeML document containg relevant experiment metadata (optional)
2. Importing the EnzymeML document and using NMRpy to process and analyze the NMR data, adding the resulting concentration time-course data back to the EnzymeML document

### 🚀 Getting Started

To get started, you will need to install the NMRpy library and other dependencies. You can do this either by running the respective cells in the two notebooks once, or by running the following commands:

```bash
python -m pip install git+https://https://github.com/NMRPy/nmrpy@adapt-to-pydantic-v2
python -m pip install matplotlib ipyfilechooser rich pyenzyme
```

### 🧪 About the Data

The data used in this tutorial is a real NMR dataset from Johann Rohwer's lab. It is a study of an enzymatic cascade comprised of the Dephosphorylation of 3-Phospoglycerate to 2-Phosphoglycerate and the Glycolysis to Phosphoenolpyruvate using whole-cell lysate. The data was collected using a 400 MHz Varian NMR spectrometer.

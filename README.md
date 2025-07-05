# ⚡ Zeta_Converter

This repository contains the Simulink model and PCB design files for a **Zeta DC-DC Converter**, created using **MATLAB Simulink** and **EasyEDA**.

## 📦 Contents

Zeta_Converter/
├── Zeta_Converter.slx            - Simulink model
├── Zeta_ConverterDCDC.prj        - Simulink project (optional)
├── ZetaPCB/                      - EasyEDA PCB and schematic files
│   ├── schematic.json
│   ├── layout.json
│   └── ...
└── README.md

## 🧪 How to Open in MATLAB

Option 1: Using `.slx` file

1. Open MATLAB
2. Navigate to this folder:
   `Zeta_Converter`
3. In the Command Window, run:

   open('Zeta_Converter.slx')

Option 2: Using `.prj` file

1. Open MATLAB
2. Navigate to this folder:
   `Zeta_Converter`
3. In the Command Window, run:

   simulinkproject('Zeta_ConverterDCDC.prj')

> Requires MATLAB with Simulink installed (R2020 or later recommended)

## 💡 How to Open in EasyEDA

1. Go to: https://easyeda.com
2. Click **File → Open Project**
3. Upload `.json` files from the `ZetaPCB/` folder:
   - `schematic.json`
   - `layout.json`

> You’ll be able to view and edit the schematic and PCB layout in your browser.

## 🛠 Tools Used

- MATLAB Simulink
- EasyEDA Online PCB Editor

## 👤 Author

Harshal Rudraksha  
Electronics & Communication Engineering  
Indian Institute of Technology Indore

## 🧠 License

MIT License – free to use, modify, and distribute with credit.

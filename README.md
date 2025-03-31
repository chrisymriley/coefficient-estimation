# Coefficient Estimation

## Intro
There are 2 notebooks. 

1. coefficient-estimation: this is incorrect, and is more simple framing of the problem, where it is assumed that the coefficient is consistent across the tasks. 
2. coefficient-estimation-grouptask: I think this is the correct formulation, where coefficients are calculated per group and task

Group is essentially the column (or I think it was component or product type)
Task is e.g. cleaning as we used in example
Work Package- same. For each work package there are several tasks, the counts are displayed for each task across all groups.
The values in the input data are the counts. 
The y/ independent variable is total time. 

--- 

## 1. How to run
### 1.1 Create Virtual Environment
```bash
python -m venv venv
```

### 1.2 Activate Virutal Environment (bash)
```bash
source venv/bin/activate
```

### 1.2 Activate Virutal Environment (windows powershell)
```PS
.\venv\Scripts\Activate.ps1
```

### 1.3 Install Requirements (bash or powershell)
```bash
pip install -r requirements.txt
```
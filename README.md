# 🖼️ Image Degradation Robustness Analysis

This project evaluates how image degradation techniques — **Gaussian Noise** and **JPEG Compression** — impact object or face detection performance.

---
[![PDF Preview](https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model/blob/main/minor-project-report.jpg)](https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model/blob/main/minor-project-report.pdf)



## ⚙️ Setup

### 1. Clone the Repository

``` bash
git clone https://github.com/Mshahnawaz1/Robustness-of-Yolo8n-Model.git
```
``` bash
cd Robustness-of-Yolo8n-Model
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv venv
```

Activate it:

```
venv\Scripts\activate
```

### 3. Install Dependencies

```
pip install -r requirements.txt
```

---

## 🚀 Run the Analysis

Run the main jupyter file to perform experiments and generate results:

---

## 📈 Outputs

- **Visual Plot:** Comparison between original and degraded images
    
- **Metrics Plot:** Visualization of Recall and IoU decay under different degradation levels
    

---

---

## 📊 Insights

- **JPEG Compression:** Causes a _sharp decline_ in Recall due to blocking artifacts
    
- **Gaussian Noise:** Leads to a _gradual performance decay_
    

---

## 🤝 Contributing

Contributions are welcome!

1. Fork this repository
    
2. Create a new branch
    
3. Commit your changes
    
4. Push to your branch
    
5. Open a Pull Request

# 🔥 PyTorch MNIST & BERT Coffee Review Tutorials

ยินดีต้อนรับสู่โปรเจกต์ตัวอย่างการใช้ **PyTorch** สำหรับผู้เริ่มต้น!  
ใน Repository นี้ คุณจะได้เรียนรู้การสร้างโมเดล **Neural Network** และ **BERT** เพื่องานต่างๆ ดังนี้:

## 📚 เนื้อหา

### 1. MNIST Handwritten Digit Classification
- ใช้ PyTorch เพื่อสร้าง Neural Network อย่างง่าย
- เทรนโมเดลด้วยชุดข้อมูล **MNIST** (ภาพลายมือตัวเลข 0-9)
- ประเมินผลความแม่นยำของโมเดล
- บันทึก และโหลดโมเดลที่เทรนแล้ว

📄 Notebook: `PyTorch_Tutorials.ipynb`

### 2. Sentiment Analysis บนรีวิวกาแฟด้วย BERT
- ใช้ **BERT (Bidirectional Encoder Representations from Transformers)** สำหรับวิเคราะห์ความรู้สึกจากรีวิวกาแฟ
- เตรียมข้อมูลรีวิว, ทำความสะอาดข้อความ (Text Cleaning)
- แปลงคะแนนรีวิวเป็น Sentiment (Positive/Negative)
- ฝึก BERT ในการจำแนกรีวิว
- ประเมินประสิทธิภาพโมเดล

📄 Notebook: `BERT_Coffee_Review_Tutorial.ipynb`

---

## ⚙️ วิธีการติดตั้งและรันโปรเจกต์

1. Clone โปรเจกต์:
```bash
git clone https://github.com/saranpreechakarm/PyTorch-Tutorials.git
cd your-repo-name
```

2. สร้าง Virtual Environment และติดตั้ง Dependencies:
```bash
python -m venv env-pytorch
source env-pytorch/bin/activate    # (Linux/Mac)
env-pytorch\Scripts\activate       # (Windows)

pip install -r requirements.txt
```

3. เพิ่ม Environment ให้ Jupyter ใช้งาน:
```bash
python -m ipykernel install --user --name=env-pytorch --display-name "Python (env-pytorch)"
```

4. เปิด Jupyter Notebook:
```bash
jupyter notebook
```
แล้วเลือก Kernel "Python (env-pytorch)" ก่อนรันโค้ด

---

## 📦 Requirements

- Python 3.8+
- torch
- torchvision
- transformers
- pandas
- scikit-learn
- matplotlib
- tqdm

(รายละเอียดทั้งหมดอยู่ใน `requirements.txt`)

---

## ✨ สิ่งที่คุณจะได้เรียนรู้

- การใช้ PyTorch ในการสร้าง Neural Network เบื้องต้น
- การจัดการ Dataset ด้วย PyTorch DataLoader
- การนำ BERT มาประยุกต์กับงาน NLP จริงๆ
- การเตรียมและทำความสะอาดข้อมูลข้อความ (Text Preprocessing)
- การประเมินผลโมเดลด้วย Accuracy และ Classification Report

---

## 🖼️ ตัวอย่าง Output

- เทรนโมเดล MNIST ได้ Accuracy สูงถึง ~97%
- เทรนโมเดล BERT วิเคราะห์รีวิวกาแฟด้วยความแม่นยำสูง

# 🎯 Capstone Project – Analisis Dataset Diabetes
Capstone Project: Data Classification &amp; Summarization using IBM Granite

## 📌 Project Overview
Proyek ini bertujuan untuk menganalisis dataset publik mengenai **diabetes** dengan tujuan menemukan faktor risiko utama yang berkontribusi terhadap kemungkinan seseorang terkena diabetes.  
Latar belakang: prevalensi diabetes semakin meningkat, tetapi deteksi dini sering terlambat sehingga pasien baru terdiagnosis saat komplikasi sudah muncul.  
Pendekatan dilakukan dengan bantuan **IBM Granite Models** untuk mendukung analisis, klasifikasi, serta summarization insight agar proses lebih cepat, interaktif, dan mudah dipahami.

---

## 📊 Dataset
- **Sumber dataset**: [Kaggle – Diabetes Dataset for Beginners](https://www.kaggle.com/code/melikedilekci/diabetes-dataset-for-beginners/input)  
- **Jumlah data**: 768 baris, 9 kolom  
- **Fitur utama**:  
  - Pregnancies → jumlah kehamilan  
  - Glucose → kadar gula darah  
  - BloodPressure → tekanan darah  
  - SkinThickness → ketebalan kulit  
  - Insulin → kadar insulin  
  - BMI → indeks massa tubuh  
  - DiabetesPedigreeFunction → riwayat keluarga diabetes  
  - Age → usia pasien  
  - Outcome → label target (1 = diabetes, 0 = non-diabetes)  

---

## ⚙️ Analysis Process
1. **Preprocessing Data**  
   - Memuat dataset dengan `pandas`, memeriksa *missing values* dan *outlier*.  
   - Normalisasi fitur numerik bila diperlukan.  
   - ➝ memastikan dataset bersih & siap dianalisis.  

2. **Exploratory Data Analysis (EDA)**  
   - Statistik deskriptif (mean, median, distribusi).  
   - Visualisasi distribusi Outcome (0 = non-diabetes, 1 = diabetes).  
   - Heatmap korelasi antar variabel.  
   - ➝ memahami pola & hubungan antar fitur.  

3. **AI-Powered Analysis (IBM Granite)**  
   - Query dataset dengan bahasa natural via LangChain DataFrame Agent.  
   - Contoh: *“What is the average glucose level of diabetic patients?”*.  
   - ➝ analisis lebih interaktif & cepat.  

4. **Text Classification (NLP)**  
   - Contoh *patient feedback* diklasifikasikan Granite menjadi **Positive** / **Negative**.  
   - ➝ mencontohkan fleksibilitas Granite di data teks.  

5. **Summarization Insight**  
   - Granite merangkum insight dalam Bahasa Indonesia.  
   - ➝ memudahkan interpretasi hasil untuk stakeholder non-teknis.  

---

## 🔎 Insight & Findings
- **Glucose** → pasien diabetes punya rata-rata **141.2**, non-diabetes hanya **110.6**.  
- **BMI** → lebih tinggi pada pasien diabetes, obesitas berhubungan dengan peningkatan risiko.  
- **Age** → pasien usia **>40 tahun** lebih sering terdiagnosis diabetes.  
- **Pregnancies** → semakin banyak kehamilan, semakin besar potensi diabetes.  
- **Distribusi Outcome** → 35% pasien terdiagnosis diabetes.  
- **Korelasi** → Glucose dan Insulin punya korelasi positif meskipun ada missing data.  
- **AI Granite Insight** → *“Pasien diabetes cenderung memiliki Glucose, BMI, Age, dan jumlah kehamilan lebih tinggi dibanding non-diabetes.”*  

---

## ✅ Conclusion & Recommendations
### Conclusion
- Faktor risiko utama diabetes: **Glucose tinggi, BMI berlebih, usia lanjut, dan jumlah kehamilan**.  
- AI Granite mempercepat analisis dengan insight yang naratif & mudah dipahami.  

### Recommendations
1. **Skrining rutin** → khususnya pada pasien dengan Glucose > 140, BMI tinggi, dan usia > 40 tahun.  
2. **Program edukasi gaya hidup sehat** → diet seimbang & olahraga untuk mencegah obesitas.  
3. **Pemanfaatan AI** → gunakan Granite untuk interpretasi data medis sehingga tenaga kesehatan bisa ambil keputusan lebih cepat.  

---

## 🤖 AI Support Explanation
- **Model**: IBM Granite 3.3-8B Instruct (via Replicate API).  
- **Integrasi**: LangChain `create_pandas_dataframe_agent` untuk menghubungkan Granite dengan dataset.  
- **Peran AI**:  
  - Classification: klasifikasi teks (feedback pasien).  
  - Summarization: insight otomatis dari hasil analisis.  
  - Query DataFrame: menjawab pertanyaan numerik langsung dari dataset.  
- **Manfaat AI**:  
  - Analisis lebih cepat & interaktif.  
  - Insight mudah dipahami stakeholder non-teknis.  
  - Mendukung rekomendasi yang actionable.  

---

## 📂 Repository Content
- `data/diabetes (1).csv` → dataset mentah  
- `notebook/Capstone-Project.ipynb` → kode analisis di Colab  
- `presentation/Analisis Dataset Diabetes dengan IBM Granite.pdf` → presentasi proyek  
- `README.md` → dokumentasi proyek  

---

## 🔗 Link Penting
- **Dataset**: [Kaggle – Diabetes Dataset for Beginners](https://www.kaggle.com/code/melikedilekci/diabetes-dataset-for-beginners/input)  
- **Colab Notebook**: https://colab.research.google.com/drive/1tVY8RIPqsmUgctD2Oj_z2Df2IgioL7w9?usp=sharing  
- **GitHub Repository**: [Link Repo kamu di sini]  

---


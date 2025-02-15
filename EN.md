### **Age and Gender Detection**

## **📌 Project Description**  
This project leverages **Deep Learning** and **Computer Vision** to detect **the age and gender of individuals from images, videos, and webcams**. The model is powered by **OpenCV and pre-trained Deep Neural Networks (DNNs)** for accurate predictions.  

---

## **Project Features**  
✔ Detects **age and gender** from images, videos, and webcam input  
✔ Uses **pre-trained models** for higher accuracy  
✔ Processes input in **real-time**  
✔ Displays **FPS** on frames to monitor model performance  
✔ Can be tested on **images, stored videos, and webcam feeds**  

---

## **📌 How to Run**
### **1. Clone the repository**  
First, download the project code:

```sh
git clone https://github.com/AliShafiee2003/Age-and-Gender-Detection.git
cd Age-and-Gender-Detection
```

---

### **2. Install requirements**  
Install the necessary packages by running:

```sh
pip install -r requirements.txt
```

---

### **3. Run the application**
#### **📸 Run the model on an image**  
To test the model on an image, use the following command:

```sh
python app.py --image images/kid.jpg
```

#### **📹 Run the model on a video**  
To test the model on a video:

```sh
python app.py --video videos/sample.mp4
```

#### **🎥 Run the model on a webcam**  
To test the model with the laptop’s webcam or an external camera, use:

```sh
python app.py --webcam
```

---

## **📸 Sample Output**
**🔹 Processed sample image:**
![Sample](outputs/result1.jpg)
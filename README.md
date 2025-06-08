# 🚘 Complete Self-Driving Car Simulation Project

A **Self-Driving Car**, also called an autonomous vehicle, is a car that uses sensors, AI models, and deep learning to drive itself without human input. This project demonstrates a simulation of such a car by integrating signal detection, lane tracking, and real-time control, all inside a virtual environment powered by **Udacity’s Self-Driving Car Simulator**.

Outputs :
1) signal detection : 
![Screenshot 2025-06-05 130809](https://github.com/user-attachments/assets/be6245f9-a98b-4d81-89f0-a0965f5511ec)
![Screenshot 2025-06-05 130824](https://github.com/user-attachments/assets/e52e6430-c839-4128-82f3-6f68637d445a)

2) Lane detection :
   ![Lane_Input_output](https://github.com/user-attachments/assets/64e6f2e2-cf10-40da-b91f-a879a109dd3c)

3) Snapshot of the GUI during live simulation
![Screenshot 2025-06-06 115454](https://github.com/user-attachments/assets/0a35145e-104b-4bb9-9e8c-136778bdc91c)
   




## 🧠 Key Features

- 🚦 Signal Detection using CNN and Traffic Sign Dataset
- 🛣️ Lane Detection using Deep Learning (MapNet)
- 📸 Input from virtual sensors (via Unreal Engine)
- 🕹️ Live GUI interface for simulation control
- 📊 Real-time accuracy evaluation

---

## 📥 Simulator Download

🔗 Download and install the [Udacity Self-Driving Car Simulator](https://github.com/Sharadpatil03/Self-driving-Car-Simulator)

---

## 🚀 How to Run This Project

### ✅ STEP 1: Clone the Repository

bash : 
git clone https://github.com/Sharadpatil03/Self-driving-Car-Simulator
cd Self-driving-Car-Simulator

 STEP 2: Create and Activate Virtual Environment
bash :
conda create -n sdcar python=3.7 -y
conda activate sdcar

STEP 3: Install Required Packages
bash :
pip install -r requirements.txt

STEP 4: Start the Simulation
python drive.py


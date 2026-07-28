# Hi there, I'm Xavier Peña 👋

I am a **Data Scientist**, **Data Engineer**, and **Full-Stack Developer** focused on building robust data pipelines, scalable backend environments, real-time cybernetic systems, and research-driven machine learning models. 

With a strong academic background in systems design, database optimization, digital signal processing (DSP), and neural computation, I enjoy bridging the gap between hardware telemetry, theoretical computer science, and software engineering. My goal is to apply my skills to cutting-edge research environments (such as the **Okinawa Institute of Science and Technology - OIST**) and advanced industry roles in Data Science, DataOps, and Robotics.

---

## 🛠️ Tech Stack & Skills

- **Languages:** Python, SQL (PL/pgSQL), Java, TypeScript, HTML5/CSS3/JavaScript
- **Data Engineering & BI:** PostgreSQL, Pentaho Data Integration (PDI), MinIO (S3), Kimball Star Schema design, Mondrian OLAP Cubes, Metabase, Saiku
- **AI, DSP & Scientific Computing:** PyTorch, Scikit-Learn, NumPy, SciPy (Signal/Fourier), Librosa, CatBoost, XGBoost, MediaPipe, VGG-19, Hopfield Associative Memory, Zero-phase Digital Filtering
- **Signal Processing & Robotics:** BrainFlow API (EEG/EMG streaming), serial telemetry (UART), Arduino controllers, zero-phase digital filtering
- **Backend & Full-Stack Development:** FastAPI, Django, REST APIs, Streamlit, Ionic, Angular, Capacitor, Docker, Git

---

## 🚀 Featured Projects

Here are the key projects I have designed and implemented:

### 📊 Data Engineering & Databases

#### 1. [ENEMDU Data Warehouse & Machine Learning Pipeline](https://github.com/XavierPenaA/enemdu-data-warehouse)
*An end-to-end Data Engineering and Data Science pipeline built to analyze socio-economic and employment trends in Ecuador.*
- **Ingestion & ETL:** Python script uploads raw SPSS/CSV datasets to a local **MinIO S3** bucket; **Pentaho Data Integration (PDI)** cleans the data (Silver layer) and loads it into a **PostgreSQL** star schema (Gold layer).
- **OLAP & BI:** Built multi-dimensional OLAP cubes via **Mondrian XML Schema** and visual reports with **Metabase** (automated via Python script configurations).
- **Machine Learning:** Implemented a predictive pipeline using **SMOTE** to handle class imbalances and trained **CatBoost** and **XGBoost** models to classify employment status and predict incomes.

#### 2. [Smart Weather Monitoring & Alerts System](https://github.com/XavierPenaA/weather-monitoring-alerts)
*A database-intensive full-stack backend-centric application showing advanced database design and API integration.*
- **Database Engine:** Implemented a **PostgreSQL** schema featuring composite indexes, complex views, **PL/pgSQL stored procedures** (for automated alerts checking), and a trigger-based **JSONB auditing system**.
- **Services:** Built a **FastAPI** REST server that queries meteorological statistics from the Open-Meteo API and saves records, connected to a **Streamlit** visualization dashboard.

---

### 🧠 AI, DSP & Scientific Computing

#### 3. [Digital Signal Processing (DSP) Audio Toolkit](https://github.com/XavierPenaA/dsp-audio-toolkit)
*A comprehensive digital signal processing and analysis toolkit for audio waveforms.*
- **Song Identification:** Features a desktop Tkinter application that calculates and compares peak frequencies from short-time Fourier spectrograms, applying a **Hann Window** to mitigate spectral leakage.
- **Equalizer & Filter:** Implements frequency-domain filtering ($Y(j\omega) = X(j\omega) \cdot H(j\omega)$) via the **Fast Fourier Transform (FFT)**, allowing users to apply custom low-pass (bass boost) and band-pass (telephony voiceband) filters, saving output WAV files and rendering 8-panel diagnostic waveform plots.

#### 4. [Neural Style Transfer (NST) Web Application](https://github.com/XavierPenaA/neural-style-transfer-app)
*An interactive deep learning application that synthesizes artistic images using convolutional neural networks.*
- **Deep Learning:** PyTorch implementation of the Gatys et al. algorithm utilizing a pre-trained **VGG-19** model.
- **Optimization Study:** Comparative analysis of **L-BFGS** vs. **Adam** optimization solvers, demonstrating L-BFGS's superiority in style transfer convergence.
- **Web App:** Built an asynchronous Flask backend that executes GPU-accelerated transfers in background threads, hooked to a modern responsive HTML/CSS/JS frontend.

#### 5. [Hopfield Face Recognition (Bio-Inspired AI)](https://github.com/XavierPenaA/hopfield-face-recognition)
*A research-oriented computer vision system that implements recurrent neural networks from scratch.*
- **Neuro-AI:** Custom implementation of a recurrent **Hopfield Network** using Hebbian learning rules and asynchronous update dynamics to serve as associative memory.
- **Feature Extraction:** Leverages **MediaPipe Face Mesh** to extract grayscale intensities from 67 key landmark nodes, binarizing them into descriptor vectors to serve as attractor states.
- **UI:** Interactive Tkinter and Matplotlib GUI to train images and test recognition on noisy/corrupted face inputs.

---

### 🤖 Robotics, Full-Stack & IoT Systems

#### 6. [ELEGOO Smart Car - Keyboard & Brain-Computer Interface (BCI)](https://github.com/XavierPenaA/elegoo-bci-smart-car)
*A real-time robotics and cybernetics controller connecting human biosignals with physical hardware.*
- **DSP & BCI:** Streams real-time EEG and EMG data from an OpenBCI headband using the **BrainFlow** API. Cleans signals with **Notch and zero-phase 4th-order Butterworth bandpass filters** to isolate EOG eye movement and EMG muscle activity.
- **Gesture Classification:** Features custom-developed feature engineering formulas to detect symmetric blinks (Forward), asymmetric winks (Left/Right), and jaw clenches (Backward).
- **Hardware Serial:** Sends ASCII command codes via **Serial/UART** (using `pyserial`) to steer a physical Arduino-based ELEGOO Smart Car, incorporating manual keyboard overrides using ctypes Windows API hooks.

#### 7. [IoT Air Quality Monitoring & Device Management System](https://github.com/XavierPenaA/iot-air-quality-system)
*A cross-platform hybrid mobile and web application for managing IoT sensor grids in industrial plants.*
- **Backend API:** Built a **Django** REST server managing entities like plant zones, IoT devices, telemetry sensors ($CO_2$, $PM_{2.5}$, temp), and automatic event triggers. Incorporates a polymorphic database schema for device maintenance logging and Role-Based Access Control (RBAC).
- **Frontend App:** Implemented a hybrid mobile and web frontend using **Ionic**, **Angular**, and **Capacitor** to display real-time sensor analytics, historical trends, and system status.

#### 8. [Gym Management System with Automated Notifications](https://github.com/XavierPenaA/gym-management-system)
*A Java desktop application built using the MVC pattern featuring Twilio integration for automated billing alerts.*
- **Architecture:** Rigid implementation of the **Model-View-Controller (MVC)** architectural pattern separating Swing layouts from business processes.
- **WhatsApp Integration:** Built a messaging manager utilizing the **Twilio SDK** to automatically generate invoices and send billing notifications to members.
- **Persistence Layer:** Implemented lightweight binary data persistence using native **Java Object Serialization** (`java.io.Serializable`) to read and write system state to local data files.

---

## 📬 Connect with me

- **LinkedIn:** [Xavier Peña on LinkedIn](https://www.linkedin.com/in/xavier-pena)
- **Email:** [xavier.pena@ucuenca.edu.ec](mailto:xavier.pena@ucuenca.edu.ec)
- **GitHub:** [github.com/XavierPenaA](https://github.com/XavierPenaA)

*“The best way to predict the future is to invent it.”*

# Xavier Peña

Software Engineer with a research focus on machine learning, data engineering, and computational intelligence. I build systems that span the full stack — from low-level hardware interfaces and biosignal processing to data pipelines, deep learning models, and web applications.

---

## Technical Stack

**Languages:** Python, SQL (PL/pgSQL), Java, TypeScript, HTML5/CSS3/JavaScript

**Data Engineering & BI:** PostgreSQL, Pentaho Data Integration (PDI), MinIO (S3), Kimball Star Schema, Mondrian OLAP Cubes, Metabase, Saiku

**AI & Scientific Computing:** PyTorch, Scikit-Learn, NumPy, SciPy, Librosa, CatBoost, XGBoost, MediaPipe, VGG-19, Hopfield Networks

**Signal Processing & Robotics:** BrainFlow API (EEG/EMG), zero-phase Butterworth filtering, serial telemetry (UART), Arduino

**Backend & Infrastructure:** FastAPI, Django, REST APIs, Streamlit, Ionic, Angular, Capacitor, Docker, Git

---

## Projects

### Data Engineering & Databases

#### [ENEMDU Data Warehouse & Machine Learning Pipeline](https://github.com/XavierPenaA/enemdu-data-warehouse)
End-to-end pipeline for analyzing socio-economic and employment trends in Ecuador.
- Raw SPSS/CSV ingestion to MinIO S3; cleaned via Pentaho PDI into a PostgreSQL Kimball star schema.
- Multi-dimensional OLAP cubes via Mondrian XML Schema with Metabase reporting.
- Predictive pipeline with SMOTE oversampling and CatBoost/XGBoost classifiers for employment and income modeling.

#### [Smart Weather Monitoring & Alerts System](https://github.com/XavierPenaA/weather-monitoring-alerts)
Database-intensive backend application demonstrating advanced PostgreSQL design patterns.
- Schema features composite indexes, complex views, PL/pgSQL stored procedures, and a trigger-based JSONB auditing system.
- FastAPI REST server integrating the Open-Meteo API, connected to a Streamlit analytics dashboard.

---

### AI, DSP & Scientific Computing

#### [Digital Signal Processing (DSP) Audio Toolkit](https://github.com/XavierPenaA/dsp-audio-toolkit)
Desktop toolkit for audio signal analysis and frequency-domain processing.
- Song identification via short-time Fourier spectrogram comparison with Hann windowing.
- Frequency-domain filtering ($Y(j\omega) = X(j\omega) \cdot H(j\omega)$) via FFT for custom low-pass and band-pass filters, with WAV export and 8-panel diagnostic plots.

#### [Neural Style Transfer (NST) Web Application](https://github.com/XavierPenaA/neural-style-transfer-app)
Interactive deep learning application for artistic image synthesis using CNNs.
- PyTorch implementation of the Gatys et al. algorithm using a pre-trained VGG-19 feature extractor.
- Comparative study of L-BFGS vs. Adam optimizers for style transfer convergence.
- Asynchronous Flask backend executing GPU-accelerated transfers, with a responsive HTML/CSS/JS frontend.

#### [Hopfield Face Recognition (Bio-Inspired AI)](https://github.com/XavierPenaA/hopfield-face-recognition)
Research implementation of recurrent neural networks for associative memory.
- Custom Hopfield Network built from scratch using Hebbian learning rules and asynchronous update dynamics.
- Feature extraction via MediaPipe Face Mesh: 67 landmark nodes binarized into descriptor vectors as attractor states.
- Interactive Tkinter/Matplotlib GUI for training and testing recognition on corrupted face inputs.

---

### Robotics, Full-Stack & IoT

#### [ELEGOO Smart Car - Keyboard & Brain-Computer Interface (BCI)](https://github.com/XavierPenaA/elegoo-bci-smart-car)
Real-time robotics controller mapping human biosignals to physical hardware commands.
- Real-time EEG/EMG streaming via BrainFlow API, cleaned with Notch and zero-phase 4th-order Butterworth bandpass filters.
- Custom feature engineering to classify symmetric blinks (Forward), asymmetric winks (Left/Right), and jaw clenches (Backward).
- ASCII command transmission over Serial/UART to an Arduino-based ELEGOO Smart Car, with keyboard overrides via ctypes Windows API hooks.

#### [IoT Air Quality Monitoring & Device Management System](https://github.com/XavierPenaA/iot-air-quality-system)
Cross-platform mobile and web application for managing industrial IoT sensor grids.
- Django REST backend managing plant zones, devices, telemetry sensors (CO2, PM2.5, temperature), and polymorphic maintenance logging with RBAC.
- Ionic/Angular/Capacitor frontend for real-time sensor analytics, historical trends, and system status.

#### [Gym Management System with Automated Notifications](https://github.com/XavierPenaA/gym-management-system)
Java desktop application using MVC pattern with Twilio-based billing automation.
- Strict MVC separation of Swing UI from business logic.
- Twilio SDK integration for automated invoice generation and WhatsApp billing notifications.
- Lightweight persistence via Java Object Serialization.

---

## Contact

- **LinkedIn:** [xavier-pena](https://www.linkedin.com/in/xavier-pena)
- **Email:** [xavier.pena@ucuenca.edu.ec](mailto:xavier.pena@ucuenca.edu.ec)
- **GitHub:** [XavierPenaA](https://github.com/XavierPenaA)

---

*"The best way to predict the future is to invent it."*

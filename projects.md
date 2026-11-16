# 📊 Project Details

Detailed information, features, and links for all my projects.

---

## WasteRefine (Academic Thesis)

An academic research study on deep learning-based semantic segmentation for automated recyclable waste sorting in Material Recovery Facilities (MRFs).

### 🔗 Links
- **GitHub Repository:** [ahnaf-iqbal/WasteRefine](https://github.com/ahnaf-iqbal/WasteRefine)
- **Dataset:** [WasteRefine on Roboflow Universe](https://universe.roboflow.com/talha-ljqb5/wasterefine)
- **Executive Summary:** [RESEARCH_SUMMARY.md](https://github.com/ahnaf-iqbal/WasteRefine/blob/main/RESEARCH_SUMMARY.md)

### 🚀 Key Highlights & Contributions
- **Novel Architecture:** Designed WasteRefine, an object-aware segmentation framework combining self-supervised DINOv2 Vision Transformers with a multi-scale decoder, Pyramid Pooling (PPM), Squeeze-and-Excitation (SE) attention, and boundary edge supervision.
- **Novel Dataset:** Collected and annotated the WasteRefine Dataset—the first dedicated municipal waste semantic segmentation benchmark from Bangladesh (2,213 images across 4 recyclable material categories).
- **Benchmark Evaluations:** Tested across WasteRefine, ZeroWaste-F, and SpectralWaste benchmarks, outperforming existing published baselines on cluttered and imbalanced environments.
- **Parameter Efficiency:** Demonstrated that an optimized lightweight model variant achieves strong segmentation accuracy with fewer parameters.

### 🛠️ Tech Stack & Methods
- **Domain:** Computer Vision, Semantic Segmentation, Environmental Sustainability
- **Frameworks:** PyTorch, Torchvision, Transformers (Hugging Face)
- **Backbone & Decoder:** DINOv2 (ViT-B & ViT-S), Dense Prediction Transformer (DPT), PPM, SE Attention

---

## Stockwatch Beta

An advanced, full-stack stock tracking and market analysis web application that allows users to monitor real-time stock prices, manage personalized watchlists, and receive AI-driven news summaries.

### 🔗 Links
- **Live Demo:** [https://stockwatch-olive.vercel.app/sign-in](https://stockwatch-olive.vercel.app/sign-in)
- **GitHub Repository:** [ahnaf-iqbal/stockwatch_beta](https://github.com/ahnaf-iqbal/stockwatch_beta)

### 🚀 Key Features
- **Real-Time Market Data:** Interactive price charts and financial news updates powered by the Finnhub API.
- **AI-Powered Analytics:** Integrates OpenAI API for automated news digests, welcome messages, and personalized watchlist analysis.
- **Intelligent Notification System:** Real-time in-app alerts and scheduled email notifications (via Nodemailer SMTP) with user-configurable preferences (e.g., email toggles, quiet hours).
- **Secure Authentication:** User signup, login, and session management powered by Better Auth.
- **Persistent Storage:** MongoDB database integration for managing user watchlists, settings, and notification history.

### 🛠️ Tech Stack
- **Framework:** Next.js (App Router), TypeScript
- **Database:** MongoDB
- **Styling:** Tailwind CSS, Shadcn UI
- **Authentication:** Better Auth
- **APIs & Tools:** OpenAI (AI features), Finnhub (Market data), Nodemailer (SMTP emails)


---

## Smart Car Rental System

An automated, IoT-enabled car rental prototype developed for **CSE461: Introduction to Robotics** at **BRAC University**. The system automates vehicle checkout, rental time tracking, fare computation, and facility security with zero human operator dependency.

### 🔗 Links
- **GitHub Repository:** [ahnaf-iqbal/Smart-Car-Rental-System](https://github.com/ahnaf-iqbal/Smart-Car-Rental-System)
- **Demo Video:** [Project_Demo_Video.mp4](https://github.com/ahnaf-iqbal/Smart-Car-Rental-System/blob/main/Demo_Video_and_Report/Project_Demo_Video.mp4)
- **Technical Report:** [CSE461_Project_Report.pdf](https://github.com/ahnaf-iqbal/Smart-Car-Rental-System/blob/main/Demo_Video_and_Report/CSE461_Project_Report.pdf)

### 🚀 Key Features & Highlights
- **RFID Authentication:** MFRC522 contactless access verification for registered customer cards with immediate audio-visual alarm for unauthorized swipes.
- **Automated Barrier Gate:** Servo SG90 barrier opens automatically upon verification and closes once the vehicle clears the passage.
- **Dual IR Vehicle Passage Tracking:** Sequential entry (IR1) and exit (IR2) infrared sensors ensure accurate vehicle presence detection.
- **Real-Time Duration & Fare Billing:** Arduino `millis()` timestamp tracking computes rental duration and transparently displays total fare on an I2C 16x2 LCD screen.
- **Stepper Camera Pan Surveillance:** 28BYJ-48 stepper motor + ULN2003 driver with 10kΩ potentiometer on a secondary Arduino board for smooth surveillance camera panning across rental bays.
- **Live Wi-Fi Video Streaming:** AI-Thinker ESP32-CAM streams real-time MJPEG video over local Wi-Fi to a web browser dashboard.
- **Fleet GPS Tracking:** ESP32 dev module paired with UBLOX NEO-6M GPS for live coordinates telemetry to the cloud.

### 🛠️ Tech Stack & Hardware
- **Hardware:** Arduino Uno R3 (x2), ESP32-CAM (OV2640), ESP32 Dev Module, UBLOX NEO-6M GPS, RFID RC522, 28BYJ-48 Stepper + ULN2003, SG90 Servo, 16x2 I2C LCD, IR Obstacle Sensors
- **Languages & Frameworks:** C/C++ (Arduino), FreeRTOS / ESP-IDF (ESP32), TinyGPS++, LiquidCrystal_I2C, MFRC522 SPI, HTTP Web Server
- **Concepts:** Embedded Systems, IoT, Robotics Automation, Hardware Interfacing, Bus Conflict Isolation
---

## Highway Surfer

A 3D endless runner game inspired by Subway Surfers, built using Python and OpenGL. Players navigate through a 3-lane railway system, dodging oncoming trains and obstacles by jumping, sliding, and switching lanes to survive and maximize their score.

### 🔗 Links
- **GitHub Repository:** [ahnaf-iqbal/highway_surfer](https://github.com/ahnaf-iqbal/highway_surfer)

### 🚀 Key Features & Gameplay Mechanics
- **3-Lane Navigation:** Smooth lateral movement across three rail tracks using `A` and `D` keys.
- **Dynamic Obstacle Dodging:**
  - **High Barriers:** Slide underneath with `S` (triggers smooth roll/slide rotation).
  - **Low Barriers:** Jump over with `W` (timed parabolic vertical leap).
  - **Moving Trains:** Fast-moving multi-car train obstacles requiring split-second lane switches.
- **Interactive UI & Menus:** Start screen overlay, pause toggle, real-time score counter, and persistent high score tracking.
- **Dual Perspective Mode:** Toggle between third-person chase camera and immersive first-person POV (`V` key).
- **Speed Scaling & Boosts:** Game speed dynamically scales with score thresholds; includes boost mechanics for high-speed action.

### 🛠️ Tech Stack & Concepts
- **Language:** Python
- **Graphics & Windowing:** PyOpenGL, GLUT (`OpenGL.GL`, `OpenGL.GLUT`, `OpenGL.GLU`)
- **Key Concepts:** 3D Transformations, Perspective Projection, Delta-Time Animation Loops, Collision Detection, Camera View Matrixing
---

## Student Performance Analysis

An exploratory machine learning study investigating the influence of demographic, socioeconomic, and academic attributes on student educational outcomes. Combines data preprocessing, extensive exploratory visualization, unsupervised clustering, and supervised classification.

### 🔗 Links
- **GitHub Repository:** [ahnaf-iqbal/student-performance-analysis-socioeconomic-factors](https://github.com/ahnaf-iqbal/student-performance-analysis-socioeconomic-factors)
- **Technical Report:** [Student_Performance_Analysis_Report.pdf](https://github.com/ahnaf-iqbal/student-performance-analysis-socioeconomic-factors/blob/main/Student_Performance_Analysis_Report.pdf)
- **Analysis Notebook:** [Student_Performance_Analysis_Notebook.ipynb](https://github.com/ahnaf-iqbal/student-performance-analysis-socioeconomic-factors/blob/main/Student_Performance_Analysis_Notebook.ipynb)

### 🚀 Key Highlights & Workflow
- **Data Preprocessing & EDA:** Cleans student background data, encodings, and feature scaling, alongside rich correlation heatmaps and distribution plots.
- **Unsupervised Clustering Comparison:** Evaluates and compares K-Means, K-Medoids-style centroid assignment, and Agglomerative Hierarchical Clustering across scaled feature sets.
- **Cluster Validation:** Employs Elbow analysis and Silhouette scores to determine optimal performance groupings (identifying 3 principal performance clusters).
- **Supervised Classification:** Trains a Random Forest Classifier to predict student performance tiers, evaluating precision, recall, and feature importances.
- **Actionable Educational Insights:** Identifies critical socioeconomic and behavioral determinants impacting academic achievement.

### 🛠️ Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Plotly, Scikit-Learn
- **Techniques:** Exploratory Data Analysis (EDA), K-Means & Hierarchical Clustering, Random Forest Classification, Model Evaluation

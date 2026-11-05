### Hi, I'm Walter Cárdenas 👋

**AI engineer and electronic engineer** from Ibagué, Colombia. I build AI systems that run in production and the electronics they live on, from a PCB to a cloud deployment.

- 🏥 **Medical imaging:** AortaAI-Colombia, an AI system for thoracic aortic aneurysm assessment, presented at **IOCIM 2026** (MDPI *Journal of Imaging*).
- 💬 **LLM agents:** founder of [Oratia](https://oratia.co). Our first product, **Mercabot**, takes supermarket orders on WhatsApp and Instagram.
- 🔌 **Electronics:** PCB design, microcontrollers (ESP32, Arduino, PIC), FPGA (VHDL) and industrial automation (PLC, HMI, MODBUS).
- 🎓 MSc student in Artificial Intelligence (UNIR) · B.Sc. in Electronic Engineering (Universidad de Ibagué) · English C1.

*Ingeniero electrónico e ingeniero de IA. Construyo sistemas de IA en producción y la electrónica que los soporta.*

---

### 🤖 AI projects

| Project | What it does | Stack |
|---|---|---|
| **AortaAI-Colombia** | End-to-end CT angiography pipeline for thoracic aortic aneurysms: aorta segmentation, centerline, perpendicular diameters per Ishimaru zone and a clinical risk score. **2.48 mm mean error vs. an expert radiologist (r = 0.957, 43 CTA studies).** | PyTorch · nnU-Net / TotalSegmentator · VMTK · SimpleITK · FastAPI |
| **Mercabot** | LLM ordering assistant for supermarkets, in production on WhatsApp and Instagram: agent with 11+ tools, voice notes, online payments. Hybrid search (RAG) raised catalogue accuracy from **70 % to 88 %**. | Claude API · FastAPI · PostgreSQL + pgvector · Next.js · Docker · AWS |
| [**NailaV2-AWS**](https://github.com/walterandres23/NailaV2-AWS) | Bilingual virtual assistant for small hotels: bookings, rates, services and local tourist guidance. | Amazon Bedrock · LangChain · RAG · Python |

### 🔌 Electronics projects

| Project | What it does | Stack |
|---|---|---|
| **YouHome** | 1:20 smart home model with two ESP32 boards on a **custom PCB** (designed in EasyEDA, manual routing, made by JLCPCB). Controlled over MQTT from a Node-RED dashboard, a mobile panel and Google Assistant voice commands; temperature, light, fingerprint access, servos and a water pump. | ESP32 · MQTT · Node-RED · EasyEDA · DHT22 |
| **Gesture-controlled robotic arm** | 5-DoF arm that follows your hand: MediaPipe detects 21 hand landmarks in Python and sends commands over serial to an ESP32 on a custom servo-driver PCB. | Python · MediaPipe · OpenCV · PySerial · ESP32 |
| [**Robot car**](https://github.com/walterandres23/robot-car-f1) | Formula 1-inspired car: chassis designed in SolidWorks and Fusion 360, laser-cut MDF base and 3D-printed motor mounts. An Arduino with a dual motor driver (Pololu MC33926) takes commands over Bluetooth (HC-05) from a custom mobile app. | Arduino · HC-05 Bluetooth · MC33926 · App Inventor · SolidWorks · Fusion 360 |

<sub>The electronics projects were university team projects (Universidad de Ibagué); each repository credits the full team.</sub>

---

### 🛠️ Tools I use

**AI and data:** Python · PyTorch · scikit-learn · Claude and OpenAI APIs · RAG · pgvector · NumPy · pandas<br>
**Medical imaging:** nnU-Net · TotalSegmentator · VMTK · SimpleITK · ITK · 3D Slicer · DICOM / NIfTI<br>
**Backend and cloud:** FastAPI · PostgreSQL · Docker · GitHub Actions · AWS · Cloudflare · Linux · n8n · MCP<br>
**Computer vision:** OpenCV · MediaPipe<br>
**Electronics and IoT:** ESP32 · Arduino · PIC · FPGA (VHDL) · MQTT · Node-RED · PLC Delta (Ladder) · HMI · MODBUS RTU<br>
**Design and fabrication:** EasyEDA (PCB) · Proteus · SolidWorks · Fusion 360 · 3D printing · laser cutting

---

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/walter-andres-cardenas-b402aa344) · [oratia.co](https://oratia.co)

# Ethics-in-AI
week 7

# 🧠 AI Assignment Portfolio (2025)

This repository documents a comprehensive portfolio of artificial intelligence (AI) concepts and applications for academic and practical evaluation. It includes theoretical analysis, hands-on implementation, ethical reflection, a futuristic concept paper, and an introduction to quantum computing in AI.

---

## 📘 Part 1: Theoretical Analysis (40%)

### ✅ Essay Questions
- **Edge AI:** Reduces latency and enhances data privacy by processing on-device (e.g., in autonomous drones).
- **Quantum vs Classical AI:** Quantum AI accelerates optimization using qubits, benefiting industries like logistics and drug discovery.
- **Human-AI Collaboration in Healthcare:** AI enhances decision-making for radiologists and nurses, increasing accuracy and efficiency.

### 🏙️ Case Study – AI-IoT in Smart Cities
- **Impact:** Improves urban sustainability through real-time traffic optimization and reduced emissions.
- **Challenges:** Data security, interoperability across diverse urban systems.

---

## ⚙️ Part 2: Practical Implementation (50%)

### 🧪 Task 1: Edge AI Prototype
- Trained image classifier for recyclable items using TensorFlow Lite.
- Demonstrated lightweight model conversion for real-time, on-device use.
- Output: `recycle_model.tflite` + accuracy report.

### 🌾 Task 2: AI-Driven IoT in Smart Agriculture
- **Sensors:** Soil moisture, temperature, humidity, light, pH, rainfall.
- **AI Model:** Random Forest or LSTM.
- **Output:** Concept proposal + data flow diagram for precision farming.

### ⚖️ Task 3: Ethics in Personalized Medicine
- **Dataset:** Cancer Genomic Atlas.
- **Issues:** Underrepresentation of minority groups, lack of transparency.
- **Solutions:** Diverse data, fairness audits, explainable models, human oversight.

---

## 🔮 Part 3: Futuristic Proposal (10%)

### 🌍 AI-Guided Atmospheric Carbon Removal (AGACR)
- Uses reinforcement learning and satellite data to guide drone-based CO₂ removal.
- Balances climate action with ethical governance to prevent misuse and ecological harm.
- Deliverable: 1-page concept paper.

---

## 🧠 Bonus Task: Quantum Computing Simulation (Extra 10%)

### 💻 Quantum Circuit with IBM Qiskit
- Implemented basic entanglement simulation in Qiskit.
- Use Case: AI-accelerated drug discovery through faster molecule simulation.

```python
from qiskit import QuantumCircuit, Aer, execute
qc = QuantumCircuit(2)
qc.h(0)
qc.cx(0, 1)
qc.measure_all()
simulator = Aer.get_backend('qasm_simulator')
result = execute(qc, simulator, shots=1024).result()
print(result.get_counts())

# Simple Reflex Agents

A collection of foundational reflex agent implementations using Python and Jupyter Notebooks. These projects demonstrate simple, condition-action (rule-based) intelligent agents interacting with dynamic environments.

---

## 🤖 Included Agents

### 1. Automatic Door Agent
* **File:** `AutomaticDoorAgent.ipynb`
* **Description:** Simulates an automated doorway system. The agent senses motion or proximity near an entrance and triggers actions (`OPEN`, `HOLD`, or `CLOSE`) based on environmental feedback to ensure smooth and safe access.

### 2. Street Light Agent
* **File:** `StreetLightAgent.ipynb`
* **Description:** Models an energy-efficient ambient light control system. The agent monitors environmental illuminance levels (lux) or time-of-day indicators to dynamically turn streetlights `ON` or `OFF`.

### 3. Reflex Temperature Agent
* **File:** `ReflexTemperatureAgent.ipynb`
* **Description:** Implements a rule-based thermostat controller. It monitors ambient room temperatures and compares them against target thresholds to control heating and cooling mechanisms automatically.

---

## 🛠️ Requirements & Setup

### Prerequisites
Make sure you have Python 3.8+ installed along with Jupyter Notebook or JupyterLab:

```bash
pip install notebook
```

### Running locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/<YOUR_USERNAME>/<YOUR_REPOSITORY_NAME>.git
   cd <YOUR_REPOSITORY_NAME>
   ```

2. **Launch Jupyter:**
   ```bash
   jupyter notebook
   ```

3. Open any `.ipynb` file and execute the code cells sequentially to view the agent logic and output simulations.

---

## 💡 Concepts Demonstrated
* Perceptions vs. Actions mapping
* Condition-action rules (`if-then` reflex logic)
* Environment state evaluation loops

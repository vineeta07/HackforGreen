# 🚦 CarbonStop AI  
## A Carbon-Aware AI Control Layer for Cities  

CarbonStop AI is a climate-intelligent urban control system that dynamically optimizes traffic infrastructure based on congestion, emissions, fairness, and real-time grid carbon intensity.

Instead of optimizing only travel time, CarbonStop AI reduces emissions when they are most environmentally harmful — during high-carbon grid periods.

---

# The Problem

Urban congestion is more than a mobility issue - it is a climate issue.

Traditional traffic systems:
- Optimize travel time
- Reduce queue length
- Improve throughput

But they ignore:
- Real-time grid carbon intensity
- Emission timing impact
- Fairness between traffic lanes
- Peak carbon hours

Cities today optimize efficiency.  
CarbonStop AI optimizes climate impact.

---

#  The Solution

CarbonStop AI introduces a carbon-aware AI control layer that dynamically adapts traffic signals based on:

- Queue length
- Waiting time
- Vehicle emissions
- Fairness score
- Real-time grid carbon intensity

When electricity generation is fossil-fuel heavy, the system aggressively minimizes idle emissions.  
When the grid is cleaner, it balances efficiency and fairness.

This transforms static traffic signals into programmable climate actors.

---

#  Core Reward Function

Traditional adaptive signal systems use:

Reward = - waiting_time

CarbonStop AI uses:

Reward =  
- waiting_time  
- vehicle_emissions  
- (grid_carbon_intensity × system_power_usage)  
- fairness_penalty  

This makes the system climate-aware, not just congestion-aware.

---

#  Architecture Overview

Traffic Simulation (SUMO)  
        ↓  
State Extraction (TraCI)  
        ↓  
Carbon-Aware Reinforcement Learning Agent  
        ↓  
Signal Decision  
        ↓  
Emission & Fairness Evaluation  
        ↓  
Urban Climate Command Center Dashboard  

---

# 🛠 Local Setup

## Clone Repo

```
git clone [https://github.com/your-username/carbonstop-ai.git](https://github.com/vineeta07/HackforGreen.git)
cd HackforGreen
```

## Run Backend

```
cd backend
pip install -r requirements.txt
uvicorn app.main:app --reload
```

Backend: http://localhost:8000

## Run Frontend

```
cd frontend
npm install
npm run dev
```

Frontend: http://localhost:3000

---

# 🧪 Demo Strategy

1. Run baseline traffic simulation  
2. Simulate carbon intensity spike  
3. Show reward change  
4. Show emission-aware adaptation  
5. Highlight fairness improvements  

---

# Impact

CarbonStop AI enables:

- Reduced peak-hour emissions  
- Lower idle fuel consumption  
- Fair lane allocation  
- Climate-aware infrastructure decisions  

This is not just traffic optimization.  
It is climate-adaptive urban intelligence.

---

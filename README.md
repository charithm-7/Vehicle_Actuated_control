# Vehicle_Actuated_control
In this project, Traffic camera imagery and deep learning are used to construct a Vehicle Actuated Control (VAC) system.  The system automatically regulates traffic signals, delivering green signals to the lanes with the most traffic after analysing real-time vehicle density from photos.
## 📊 Dataset

- **File:** `synthetic_traffic_data.csv`
- **Location:** `data/`
- **Features:**
  - `traffic`, `speed`, `congestion`, `utilization`
  - `time_sin`, `time_cos` (time encoding)
  - One-hot encoded vehicle types (`vehicle_0`, `vehicle_1`, `vehicle_2`)
  - `action`: 1 = green signal, 0 = red signal

---

## 📁 Project Structure

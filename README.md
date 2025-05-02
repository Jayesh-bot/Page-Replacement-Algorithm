


# 💾 Efficient Page Replacement Simulator

An interactive web-based simulator built using Python and Streamlit to visualize and compare three classical page replacement algorithms—FIFO, LRU, and Optimal. Designed as an educational tool to help students understand memory management concepts in operating systems.

## 📚 Project Overview

This simulator enables users to:

* Input custom page reference strings and frame sizes
* Select from FIFO, LRU, and Optimal page replacement strategies
* View side-by-side comparisons of algorithm performance
* Explore detailed step-by-step memory page replacement
* Visualize results using bar and pie charts

---

## 🛠 Features

* **Algorithms Included:**

  * FIFO (First-In-First-Out)
  * LRU (Least Recently Used)
  * Optimal (Theoretical Best)

* **Visualization:**

  * Bar chart for page faults
  * Pie chart for hit ratio
  * Step-by-step execution logs

* **User Input:**

  * Space-separated page reference string
  * Selectable number of memory frames (1–10)
  * Option to simulate one or multiple algorithms at once

---

## 🚀 Getting Started

### Prerequisites

Ensure Python 3.x is installed. Required Python packages:

```bash
pip install streamlit numpy pandas matplotlib
```

### Running the Application

```bash
streamlit run epr.py
```

This will launch the simulator in your default web browser.

## 📊 Sample Output

Given:

* Reference String: `7 0 1 2 0 3 0 4`
* Frames: `3`

| Algorithm | Page Faults | Hit Ratio (%) |
| --------- | ----------- | ------------- |
| FIFO      | 6           | 25%           |
| LRU       | 5           | 37.5%         |
| Optimal   | 4           | 50%           |

---

## 📈 Future Enhancements

* Add more algorithms (e.g., MRU, Clock, LFU)
* Export simulation results to PDF or CSV
* Animate memory page transitions
* Mobile responsiveness and UI improvements

---


---

## 📄 License

This project is licensed for academic and educational use. Please credit the authors and supervisor if reused or modified.

# ABC-Analysis
Warehouse Optimization Model Summary

1. ABC Analysis Summary (Pareto Principle)
Products were classified based on their annual consumption value (Annual Order Quantity × Unit Price):
- Class A Products (High Value): 31 products, representing the vast majority of total stock value (~13.08M TL).
- Class B Products (Medium Value): 30 products, valued at approximately 2.45M TL.
- Class C Products (Low Value): 39 products, valued at only 831K TL.

2. Warehouse Layout & Distance Optimization
Our model strategically placed high-velocity and high-value Class A products in racks closest to the dispatch/packing area (Rack-R02, 25 meters), Class B products at medium distance (Rack-R05, 60 meters), and low-demand Class C products in the furthest racks (Rack-R09, 100 meters).

As a result of this optimization:
- Current Annual Total Walking Distance: ~3.59 million meters (3,590 km)
- New (Optimized) Annual Total Distance: ~1.71 million meters (1,707 km)
- Annual Distance Saved: 1.88 million meters (1,882 km)
- Improvement Rate: 52.44%

3. Visualizations
The generated charts clearly summarize the outcome:
- ABC Analysis Pareto Curve: Shows the cumulative value increase and the 80% (Class A) and 95% (Class B) thresholds.
- Annual Travel Distance Comparison: Compares the current travel distance (orange) with the optimized distance (blue) by class, clearly highlighting the massive distance savings achieved by relocating Class A products closer to the packing area.
  Libraries and Methods Used
Libraries Used:
Pandas (pandas): The core data analytics library used for reading Excel data, managing DataFrames, and performing table manipulations (grouping, cumulative sums).
SQLite (sqlite3): Enables running an in-memory (:memory:) SQL database directly within Python to execute LEFT JOIN and GROUP BY queries without an external server setup.
NumPy (numpy): Provides operational support for numerical arrays and mathematical calculations (such as bar chart positioning).
Matplotlib & Seaborn (matplotlib.pyplot, seaborn): Utilized for professional-grade visualization of the ABC Pareto curve and the comparative bar charts for current vs. optimized travel distances.
Methods Applied:
ABC Analysis (Pareto Principle): Products were ranked in descending order based on their annual consumption value (Annual Order Quantity \times Unit Price). Thresholds of 80% and 95% were applied to classify items into Class A, Class B, and Class C.
Warehouse Relocation Optimization: High-velocity Class A items were positioned in racks closest to the dispatch/packing area, while low-demand Class C items were placed in the furthest racks to minimize walking distances.
Distance & Efficiency Simulation: Total annual round-trip walking distances were calculated in meters to quantify the exact distance saved and compute the overall percentage improvement.

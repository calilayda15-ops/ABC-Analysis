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
  

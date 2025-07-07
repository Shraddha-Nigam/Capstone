# Capstone Project
Brief Overview:
Urban parking is a limited resource, and static pricing often causes over- or under-utilization. This project implements two dynamic pricing models for 14 urban parking lots using real-time data, built from scratch with Python, Pandas, and NumPy.

Data & Features Used:
Timestamp (combined LastUpdatedDate + LastUpdatedTime)
Location ID: LotID

Features:
Occupancy, Capacity, Queue Length, Traffic Level (low, average, high), Special Day Indicator, Vehicle Type (car, bike, truck)

Visualization
Tool Used: Bokeh
Output: Real-time line plot comparing Model 1 vs Model 2 prices for each LotID

Note: In Colab, dynamic Bokeh plots may flicker or disappear; this is a platform-specific rendering issue.

=> Screenshots were captured during simulation to reflect price dynamics over time.

Assumptions
Base price is fixed at $10
Vehicle weights:
car: 1.0
bike: 0.7
truck: 1.5

Traffic mapping:
low: 1, average: 2, high: 3

Demand values vary across time and lots, so normalization is done per LotID

Conclusion
This solution:
Successfully builds two pricing models from scratch
Handles real-time dynamic inputs with a simulated streaming setup
Visualizes time-varying pricing patterns for individual lots
Complies with all guidelines using only allowed libraries (NumPy, Pandas, Bokeh)

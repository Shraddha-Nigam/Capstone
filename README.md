# Capstone Project
Brief Overview:
Urban parking is a limited resource, and static pricing often causes over- or under-utilization. This project implements two dynamic pricing models for 14 urban parking lots using real-time data, built from scratch with Python, Pandas, and NumPy.

Data & Features Used:
</br> Timestamp (combined LastUpdatedDate + LastUpdatedTime)
</br> Location ID: LotID

Features:
</br> Occupancy, Capacity, Queue Length, Traffic Level (low, average, high), Special Day Indicator, Vehicle Type (car, bike, truck)

Visualization
</br> Tool Used: Bokeh
</br> Output: Real-time line plot comparing Model 1 vs Model 2 prices for each LotID

Note: In Colab, dynamic Bokeh plots may flicker or disappear; this is a platform-specific rendering issue.

=> Screenshots were captured during simulation to reflect price dynamics over time.

Assumptions
</br> Base price is fixed at $10
</br> Vehicle weights:
</br> car: 1.0
</br> bike: 0.7
</br> truck: 1.5

Traffic mapping:
</br> low: 1, average: 2, high: 3

Demand values vary across time and lots, so normalization is done per LotID

Conclusion
</br> This solution:
</br> Successfully builds two pricing models from scratch
</br> Handles real-time dynamic inputs with a simulated streaming setup
</br> Visualizes time-varying pricing patterns for individual lots
</br> Complies with all guidelines using only allowed libraries (NumPy, Pandas, Bokeh)

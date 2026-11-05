# British Airways Data Science Simulation (Forage)

## Task 1: Lounge demand at Heathrow Terminal 3
Used Excel pivot tables and SQL on 10,000 flights to estimate how many passengers
would be eligible for each lounge tier. Route type (short-haul vs long-haul)
mattered much more than time of day.

## Task 2: Predicting customer bookings
Explored 50,000 customer bookings in Python (pandas) and trained a Random Forest
model to predict which customers complete a booking.

- Cross-validated AUC: 0.77
- Biggest factor: how far ahead customers book (purchase lead)
- Route, flight hour, length of stay and country also matter
- Sales channel and trip type barely matter

## Tools
Python, pandas, scikit-learn, matplotlib, SQL, Excel

## Files
- `BA_Customer_Booking_Prediction.ipynb`: analysis and model
- `feature_importance.png`: what drives a booking
- `summary.pdf`: one-page summary for management

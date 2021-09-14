__Topic:__ Analysis of passenger air transportation.

__Purpose:__ 
Conduct an analysis of the dependence: 
- aircraft models and the number of flights; 
- cities and number of flights.

To test the hypothesis about the difference in the average demand for tickets during various festivals and at normal times.

__Stack:__
1. A parser has been written to collect data from the site about the 11 largest festivals of 2018
2. A research analysis of the data was carried out. Using SQL defined:
- the number of flights departing in September 2018 for each aircraft model;
- the number of flights for all models of Boeing , Airbus and other aircraft in September is calculated;
- the average number of incoming flights per day for each city for August 2018 is calculated.
3. Data on the number of flights during the festivals have been prepared. The festivals that took place from July 23 to September 30, 2018 in Moscow, and the number of the week in which they took place are set. For each week from July 23 to September 30, 2018, count the number of tickets purchased for flights to Moscow. A table was obtained with information about the number of tickets purchased during the week, with a note whether the festival was held that week, the name of the festival.
4. The hypothesis of the difference in the average demand for tickets during various festivals and at normal times was tested.
5. Data analysis using Python:
- reading the table and studying the data;
- data preprocessing;
- analysis of the number of flights from the city and the aircraft model.
6. Output.

__Conclusion:__ The hypothesis about the difference in the average demand for tickets during various festivals and at normal times was not confirmed. During festivals, the demand practically does not change - just look at the ticket_amount column of the combined table and compare the values.

The number of flights depends on:
1. the class of the airport - the higher the class, the more flights
2. depending on the number of airports in the city - the more airports in the city, the more flights there are naturally
3. depending on the model of the aircraft-aircraft designed for long-distance flights make fewer flights, naturally they are in flight for more time, they need more time to prepare for the flight. During this time, small aircraft can make several flights.

__Skills and tools:__ SQL, Python, Pandas, Matplotlib, SciPy, testing statistical hypotheses.

__Project status:__ Completed.

Easy-Estimation Interface
Easy-Estimation Interface is a program designed to speed up the estimate process for home painting projects. It provides an interface for users to input measurements and select different paint qualities, and outputs the estimated cost for both supplies and labor.

How to Use
To use Easy-Estimation Interface, simply input the necessary measurements and select the desired paint quality. The program will automatically calculate the estimated cost for supplies and labor based on the input data. The output will be displayed in an easy-to-read format.

Inputs
Easy-Estimation Interface accepts integer inputs for measurements of the size of the project, including:

siding_measurement: the size of the siding in square feet
eaves_measurement: the size of the eaves in linear feet
fascia_measurement: the size of the fascia in linear feet
trim_measurement: the size of the trim in linear feet
And it also accepts a vector of paint_prices with the pricing options for each gallon of paint.

Functions
Easy-Estimation Interface utilizes two user functions:

[paint_options, total_paint_gallons] = calculatePaint(siding_measurement, eaves_measurement, fascia_measurement, trim_measurement, paint_prices)

calculatePaint() takes the inputted measurements and paint prices, calculates how many gallons of paint are needed, and provides pricing options for different types of paint.

The function returns two outputs:

paint_options: a 4x1 cell array containing the pricing options for each gallon of paint.
total_paint_gallons: the total amount of paint needed for the project.
total_labor_cost = calculateLabor(siding_measurement, eaves_measurement, fascia_measurement, trim_measurement)

calculateLabor() takes the inputted measurements, calculates the total labor hours needed, and outputs the total cost for labor.

The function returns one output:

total_labor_cost: the total cost of labor needed for the project.
Benefits
Easy-Estimation Interface can save time for estimate processes for home painting projects. It is estimated that this program can save 10 minutes for each estimate, and with over 50,000 estimates done nationally each year, that amounts to over 8,000 man-hours saved.

License
Easy-Estimation Interface is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

Future Updates
There are no current updates planned for Easy-Estimation Interface. If any updates become available, they will be added to this README file with the date and a brief description of the update.

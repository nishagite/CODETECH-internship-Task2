# CODETECH-internship-Task2
Name:Gite Nisha Bapusaheb
Company:CODETECH IT SOUKUTION
Duration:Steptember to october 2024
Mentor:Neela Santosh Kumar

Overview of Program
This C++ console application allows users to convert temperatures between Celsius, Fahrenheit, and Kelvin scales. 
The program provides a simple and intuitive interface for inputting a temperature, selecting the initial scale, and choosing a target scale for conversion. It performs the necessary calculations based on standard conversion formulas and outputs the result.
Key Features:
>Interactive Menu:
 The user is prompted to select the input and output temperature scales from a menu.
>Supported Conversions:
>Celsius to Fahrenheit
>Celsius to Kelvin
>Fahrenheit to Celsius
>Fahrenheit to Kelvin
>Kelvin to Celsiu
>Kelvin to Fahrenheit
>Edge Case Handling: The program accounts for invalid or identical input/output scale selections.

How the Program Works:
1.User Input:The user first chooses a temperature scale to convert from (Celsius, Fahrenheit, or Kelvin).The user inputs the temperature value to be converted.Finally, the user selects the target scale to convert to.
2.Conversion Logic:Based on the input, the program calls one of six conversion functions. These functions use predefined formulas for converting between the temperature scales.If the user selects the same scale for both input and output, the program notifies that no conversion is needed.
3.Output: The program displays the converted temperature in the desired scale.

Conversion Formulas:
Celsius to Fahrenheit: [ \text{Fahrenheit} = (\text{Celsius} \times \frac{9}{5}) + 32 ]
Celsius to Kelvin: [ \text{Kelvin} = \text{Celsius} + 273.15 ]
Fahrenheit to Celsius: [ \text{Celsius} = (\text{Fahrenheit} - 32) \times \frac{5}{9} ]
Fahrenheit to Kelvin: [ \text{Kelvin} = (\text{Fahrenheit} - 32) \times \frac{5}{9} + 273.15 ]
Kelvin to Celsius: [ \text{Celsius} = \text{Kelvin} - 273.15 ]
Kelvin to Fahrenheit: [ \text{Fahrenheit} = (\text{Kelvin} - 273.15) \times \frac{9}{5} + 32 ]
Example:
A user might input:
Original scale: Celsius
Temperature: 100
Target scale: Fahrenheit

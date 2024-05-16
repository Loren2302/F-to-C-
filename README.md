My goal for this project is to create a temperature conversion tool, it will convert temperatures in Celsius and Fahrenheit. I will start by defining my function which are: 
def celsius_to_fahrenheit(celsius):
    return (celsius * 9/5) + 32

def fahrenheit_to_celsius(fahrenheit):
    return (fahrenheit - 32) * 5/9
These include the math conversions as well, to carry out the calculations when the function is called. In the first cell I do have example test functions to ensure it will correctly convert before user input. Along with the math from above all calculations should be correct. 
Next to begin the user input section, I started by creating a prompt starting with celsius. Once the user enter their temperature, it will use the celsius_to_fahrenheit function to convert and print the temperature now in fahrenheit. After that is displayed it will ask for a temperature in Fahrenheit and do the same process but instead use the fahrenheit_to_celsius  function. The output prints are in this format:

print(f"{celsius_input}°C is equal to {fahrenheit_output}°F")

print(f"{fahrenheit_input}°F is equal to {celsius_output:.2f}°C")

Define Functions
↓                                               ↓ 
Celsius to fahrenheit       -      Fahrenheit to Celsius
↓
Collect use input




# CMPT 1105 Celsius To Fahrenheit Calculation

A Python example of converting celcius to fahrenheit. This demonstrates the usage of taking user input, format a string, and output appropriate string format.

```python
# Fahrenheit = 1.8C + 32

celcius = float(input("Enter a celcius value"))
fahrenheit = format(1.8 * celcius + 32, '0.1f');

print("Celcius: " + str(celcius), " Fahrenheit: " + fahrenheit)
```

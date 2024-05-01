<image align="center" alt="Milad" width = "600" src="https://d20khd7ddkh5ls.cloudfront.net/fandctempconversion.jpg"> 

<pre>def celsius_to_fahrenheit(C):
    fahrenheit = (C * 1.8) + 32
    return fahrenheit

C = float(input("Please type the temperature:"))
fahrenheit = celsius_to_fahrenheit(C)
print(f"{C} celsius degree is equal to {fahrenheit} fahrenheit degree")

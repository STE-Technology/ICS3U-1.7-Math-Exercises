# 1.7 Math Exercises

Write a solution using Python to each of the following math problems. For each solution, be sure to include:

- A descriptive program header, written as a multi-line comment. Follow the example style in the template.
- Proper naming of variables. (See [this](https://github.com/STE-Technology/ICS3U-1.3-Hello-World) documentation.)
- Comments to document your code.
- User-friendly input prompts.

## 1. Circumference
Write a program `circumference.py` that gets the radius of a circle from user input, then computes and outputs the circumference. Use the formula $c = 2\pi r$

#### Example Runtime & Test Case
```
Circumference Calculator

Enter Radius: 12.3

Result: Circumference is 77.2
```

## 2. Exponent
Write a program `exponent.py` that gets two numbers from user input, $a$ and $b$, then computes and outputs the result $a^b$

#### Example Runtime & Test Case
```
Exponent Calculator

Enter Base (a): 2
Enter Power (b): 8

Result: a^b is 256256
```

## 3. Radians
Write a program `rads.py` that gets a number from user input in degrees, then converts and outputs the equivalent value in radian measure. Use the formula $radians = degrees \times \frac{\pi}{180}$

#### Example Runtime & Test Case
```
Radian Calculator

Enter Degrees: 45

Result: 45 degrees is 0.785 radians
```

## 4. Fahrenheit to Celsius
Write a program `celsius.py` that gets a temperature from user input in Fahrenheit, then outputs the equivalent value in Celsius. Use the conversion formula $c = \frac{5}{9}(f - 32)$, where $c$ is the temperature in Celsius, and $f$ is the equivalent in Fahrenheit.

#### Example Runtime & Test Case
```
Fahrenheit to Celsius Converter

Enter Temperture in Fahrenheit: -40

Result: -40°F is -40°C
```

## 5. Miles to Kilometres
Write a program `kilometres.py` that gets a distance from user input in miles, then outputs the equivalent value in kilometres. Use the conversion formulas $m = 1.609k$ or its reciprocal $k = 0.62m$ where $m$ is the distance in miles, and $k$ is the equivalent in kilometres.

#### Example Runtime & Test Case
```
Miles to Kilometres Calculator

Enter Distance in Miles: 55

Result: 55 miles equals 88.5 km
```

## 6. Hours to Days
Write a program `hours.py` that gets a number of hours from user input, then converts it into days and hours. For example, `111 hours` would equal `4 days, 15 hours`.

#### Example Runtime & Test Case
```
Hours to Days Calculator

Enter Duration in Hours: 111

Result: 111 hours is equal to 4 days, 15 hours
```

## 7. Volume of a Sphere
Write a program `sphere.py` that gets the radius of a sphere from user input, then computes and outputs the volume of the sphere. Use the formula $\frac{4}{3}\pi r^3$ where $\pi = 3.14$.

#### Example Runtime & Test Case
```
Sphere Volume Calculator

Enter Radius: 12.3

Result: Volume is 7795
```

## 8. Future Value of an Investment
Write a program `investment.py` that calculates the future value of an investment. Prompt the user for (1) the principal amount, (2) annual interest rate as a decimal (e.g. input `0.06` for $6\%$), and (3) the number of years. Use the future value formula:

$$FV = P \times (1 + r)^n $$

Where:

- $FV$ is the future value of the investment
- $P$ is the principal amount
- $r$ is the annual interest rate, expressed as a decimal
- $n$ is the number of years the investment is held

#### Example Runtime & Test Case
```
Investment Future Value Calculator

Enter Principal Amount: 25000.00
Enter Annual Interest Rate: 0.0595
Enter Number of Years: 2

Result: Future Value of investment is 28063.51
```

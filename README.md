# Body Mass Index Calculator (IMC)

This program simple example developed in phyton with jupyter lab, calculates the Body Mass Index (IMC)

1) Get the user's weight in kilograms
```
weight = float(input("Enter your weight in kilograms: "))
```

2) Get the user's height in meters
```
height = float(input("Enter your height in meters: "))
```

3) Calculate the IMC
```
imc = weight / (height ** 2)
```

4) Print the IMC
```
print("Your IMC is: {:.2f}".format(imc))
```

5) Determine the IMC category
```
if imc < 18.5:
    print("You are underweight.")
elif imc < 25:
    print("You are normal weight.")
elif imc < 30:
    print("You are overweight.")
else:
    print("You are obese.")
```

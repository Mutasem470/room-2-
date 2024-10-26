Room 2: Control System Simulation
Simulate a control system for a hydraulic pump. Check the
pressure and maintain it between 20 and 80.

This code prompts the user to enter a pressure value and then checks if it falls within the acceptable range, providing guidance based on the input.
pressure = int(input("Enter pressure: "))


#code
if pressure < 20:
    print("Pressure is too low. Increase the pressure.")
elif pressure > 80:
    print("Pressure is too high. Decrease the pressure.")
else:
    print("Pressure is within the normal range.")

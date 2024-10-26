
pressure = int(input("Enter pressure: "))

if pressure < 20:
    print("Pressure is too low. Increase the pressure.")
elif pressure > 80:
    print("Pressure is too high. Decrease the pressure.")
else:
    print("Pressure is within the normal range.")

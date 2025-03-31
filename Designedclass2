# Base class: Vehicle
class Vehicle:
    def __init__(self, brand):
        self.brand = brand
    
    def move(self):
        pass  # To be overridden


# Subclass 1: Car (inherits from Vehicle)
class Car(Vehicle):
    def move(self):
        print(f"The {self.brand} car is driving 🚗")


# Subclass 2: Plane (inherits from Vehicle)
class Plane(Vehicle):
    def move(self):
        print(f"The {self.brand} plane is flying ✈️")


# Subclass 3: Boat (inherits from Vehicle)
class Boat(Vehicle):
    def move(self):
        print(f"The {self.brand} boat is sailing 🚤🌊")


# Testing the vehicles
vehicles = [Car("Toyota"), Plane("Boeing"), Boat("Yamaha")]

for vehicle in vehicles:
    vehicle.move()

# week5.py
class Superhero :
 def_init_(self,name,power,origin) :
    self.name = name
    self.power = power
    self.origin = origin
def introduce(self):
    return f"I am{self.name} , a superhero from {self.origin}!"
def use_power(self) :
    return f"{self.name} uses {self.power}!"
class FlyingHero(Superhero):
    def_init_(self,name,power,origin,flight_speed):
        super()._init_(name,power,origin)
        self.flight_speed = flight_speed
def use_power(self):
    return f"{self,name} soars through the skies at {self.flight_speed} mph , wielding {self.power}!"
class TechHero(superhero):
    def_init_(self, name, power, origin, gadgets) :
        super()._init_(name, power, origin)
        self.gadgets = gadgets
def use.power(self):
    return f"{self.name} deploys gadgets like {','.join(self.gadgets)} to enhance {self.power}!"
hero1 = FlyingHero("Skyblade" , "Wind Slash ," , "Cloud City", 500)
hero2 = TechHero("Circuit", "Cyber Combat", "Neo-Tokyo", ["Drones", "Hacking Tools", "EMP Blasters"])
print(her01.introduce())
print(hero1.use_power())
print(hero02.introduce())
print(her02.use_power())

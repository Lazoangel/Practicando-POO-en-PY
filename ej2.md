class Persona:
    def __init__(self, nombre, edad):
        self.nombre = nombre
        self.edad = edad

    def cumpleaños(self):
        self.edad += 1
 
p = Persona(input("Ingrese nombre: "), int(input("Ingrese edad: ")))

p.cumpleaños()
p.cumpleaños()

print(f"{p.nombre} cumple {p.edad} años")
![image](https://github.com/user-attachments/assets/47e5b921-a8a7-4d00-8304-a5141f24b4b8)

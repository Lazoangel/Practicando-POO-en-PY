class Fabrica:
    def __init__(self, llantas, color, precio):
        self.llantas = llantas
        self.color = color
        self.precio = precio

class Moto(Fabrica):
    def cantidad(self):
        print(f"La cantidad de llantas: {self.llantas}\nEl color es: {self.color}\nEl precio es: {self.precio}")

class Carro(Fabrica):
    def cantidad(self):
        print(f"La cantidad de llantas: {self.llantas}\nEl color es: {self.color}\nEl precio es: {self.precio}")

moto = Moto(2, "Gris", "$200")
print("OBJETO = moto")
moto.cantidad()

carro = Carro(4, "Negro", "$600")
print("OBJETO = carro")
carro.cantidad()
![image](https://github.com/user-attachments/assets/14973970-ea88-437a-9f44-8a0edb281d8b)

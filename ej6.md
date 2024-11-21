class Marino:
    def hablar(self):
        print("Hola, soy un animal marino!")

class Pulpo(Marino):
    def hablar(self):
        print("Hola soy un pulpo!")

class Foca(Marino):
    def __init__(self, mensaje):
        self.mensaje = mensaje

    def hablar(self):
        print(self.mensaje)

marino = Marino()
marino.hablar()  
pulpo = Pulpo()
pulpo.hablar()  

foca = Foca("Hola soy una foca!")
foca.hablar()  
![image](https://github.com/user-attachments/assets/d970d04a-4513-410e-8adf-8080580eaad5)

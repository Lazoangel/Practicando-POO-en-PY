class Calculadora:
    def __init__(self, num1, num2):
        self.num1 = num1
        self.num2 = num2

    def suma(self):
        resultado = self.num1 + self.num2
        print(f"El resultado de la suma es: {self.num1} + {self.num2} = {resultado}")

    def resta(self):
        resultado = self.num1 - self.num2
        print(f"El resultado de la resta es: {self.num1} - {self.num2} = {resultado}")

    def division(self):
        if self.num2 != 0:
            resultado = self.num1 / self.num2
            print(f"El resultado de la división es: {self.num1} / {self.num2} = {resultado}")
        else:
            print("Error: No se puede dividir por cero.")

    def multiplicacion(self):
        resultado = self.num1 * self.num2
        print(f"El resultado de la multiplicación es: {self.num1} * {self.num2} = {resultado}")

operacion1 = Calculadora(10, 5)
operacion1.suma()

operacion2 = Calculadora(20, 5)
operacion2.resta()

operacion3 = Calculadora(15, 3)
operacion3.division()

operacion4 = Calculadora(8, 4)
operacion4.multiplicacion()
![image](https://github.com/user-attachments/assets/5e850f4b-f10a-4a08-ac7a-063e8a0a29a1)

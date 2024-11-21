#Lazo Jimenez Angel 3W
class Estudiante:
    def __init__(self, nombre, nota):
        self.nombre = nombre
        self.nota = nota

    def imprimir(self):
        print(f"Nombre: {self.nombre} \nNota: {self.nota}")

    def resultados(self):
        if self.nota >= 7:
            print("Has APROBADO!")
        else:
            print("Has REPROBADO!")

# Creando instancias de la clase Estudiante y mostrando resultados
estudiante1 = Estudiante("Pedro", 5)
estudiante1.imprimir()
estudiante1.resultados()

estudiante2 = Estudiante("Elizabeth", 7)
estudiante2.imprimir()
estudiante2.resultados()
![image](https://github.com/user-attachments/assets/b47d9218-04d4-4f51-8fd3-817c2ea74d39)

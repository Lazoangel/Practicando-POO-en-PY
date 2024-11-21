class Universidad:
    def __init__(self, nombre):
        self.nombre = nombre

class Carrera:
    def carrera(self, especialidad):
        self.especialidad = especialidad

class Estudiante(Universidad, Carrera):
    def __init__(self, nombre_universidad, nombre_estudiante, edad):

        Universidad.__init__(self, nombre_universidad)
        self.nombre = nombre_estudiante
        self.edad = edad

    def mostrar_datos(self):
        print(f"El nombre del estudiante es {self.nombre}, tiene {self.edad} años, "
              f"su especialidad es {self.especialidad}. Estudia en la Universidad {self.nombre}.")

persona = Estudiante("Harvard", "Mike", 19)

persona.carrera("Ingeniería Mecatrónica")

persona.mostrar_datos()
![image](https://github.com/user-attachments/assets/68e6cc77-0272-498d-b8f8-f54c2f38c7e6)

class Estudiante:
    def __init__(self, id, nombre, fecha_nacimiento, id_curso):
        self.id = id
        self.nombre = nombre
        self.fecha_nacimiento = fecha_nacimiento
        self.id_curso = id_curso

class Curso:
    def __init__(self, id, nombre, creditos):
        self.id = id
        self.nombre = nombre
        self.creditos = creditos

class Profesor:
    def __init__(

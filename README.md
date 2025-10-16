```sql
CREATE TABLE Docentes (
    ID_Docente INT PRIMARY KEY IDENTITY(1,1),
    Nombre VARCHAR(100),
    DNI CHAR(8),
    Correo VARCHAR(100)
);

INSERT INTO Docentes (Nombre, DNI, Correo)
VALUES
('Juan Pérez', '12345678', 'juan.perez@colegio.edu'),
('María López', '87654321', 'maria.lopez@colegio.edu'),
('Carlos Gómez', '65498732', 'carlos.gomez@colegio.edu');
```

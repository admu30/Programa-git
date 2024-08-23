# mi proyecto
CREATE DATABASE ProyectoUsuarios;
USE ProyectoUsuarios;

CREATE TABLE usuarios (
    id INT AUTO_INCREMENT PRIMARY KEY,
    nombre VARCHAR(100) NOT NULL,
    edad INT NOT NULL
);
INSERT INTO usuarios (nombre, edad)
VALUES ('Juan Pérez', 30);
SELECT * FROM usuarios;
UPDATE usuarios
SET nombre = 'Juan Gómez', edad = 31
WHERE id = 1;
DELETE FROM usuarios
WHERE id = 1;

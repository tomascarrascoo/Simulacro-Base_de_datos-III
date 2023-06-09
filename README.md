# Simulacro-Base_de_datos-III

***

- 1.- SELECT * FROM piezas WHERE Color = 'rojo';

- 2.- SELECT * FROM proveedores WHERE Ciudad_proveedor = 'Madrd';

- 3.- SELECT Nombre_pieza FROM piezas WHERE Peso = (
             SELECT MAX (Peso)
             FROM Piezas
             ;

- 4.- 

- 5.- SELECT DISTINCT Nombre_proveedor
      FROM proveedores
      INNER JOIN piezas on Id_proveedor
      WHERE Color = 'azul';

- 6.-

- 7.- SELECT Nombre_proveedor
      FROM proveedores
      INNER JOIN piezas on Id_proveedor = Id_proveedor
      WHERE Peso = (
            SELECT MAX (Peso)
            FROM Piezas
            );

- 8.- SELECT * FROM piezas
      INNER JOIN proveedores ON Id_proveedor = Id_proveedor
      WHERE Ciudad_proveedor = 'Barcelona';

- 9.-

- 10.-

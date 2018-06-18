# php-path-migrate-sql

Pasos
1. Instanciar **PathMigrate**
2. Asignar los datos de conexión a la base de datos
3. Asignar la configuración de la migracion
4. Implementar el metodo de migración que se realizará
  
  Opciones:
  
      1 Migrar el path al sql (actual o nuevo), dependiendo de la config
  
      2 Migrar el nombre del archivo, con spaciados y sin caracteres (- o _) y la extensión/formato
  
5. Insertar o actualizar elementos, pasando como parametro el campo a ser actualizado

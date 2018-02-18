
use db1;

SELECT
libros.id,libros.nombre AS Titulo,autores.nombre AS Autor, editoriales.id AS Editorial
FROM
libros,editoriales,autores
WHERE
libros.id = 'fw_771-h' AND
libros.id_autor = autores.id AND
libros.id_editorial = editoriales.id;

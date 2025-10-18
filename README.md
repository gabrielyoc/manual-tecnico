# manual-tecnico
Manual Técnico 
Nombre del estudiante: Gabriel Alexander Choy Yoc 
Nombre del proyecto: Gestor Académico Inteligente 
Descripción técnica general del sistema 
El sistema “Gestor Académico Inteligente” fue desarrollado en Python y permite 
administrar los cursos de un estudiante junto con sus notas. 
Está diseñado para facilitar el control académico mediante el uso de estructuras de datos 
dinámicas como listas, pilas y colas, ofreciendo una experiencia simple, ordenada y 
funcional. 
El programa incluye opciones para registrar, actualizar, eliminar, ordenar y buscar 
cursos, además de un módulo especial para gestionar solicitudes de revisión y un 
historial de cambios de notas. 
Estructura general del código 
El sistema está organizado modularmente. 
Cada función realiza una tarea específica, lo que permite que el programa sea más fácil de 
mantener y entender. 
Un menú principal guía al usuario por las distintas opciones, y un bucle principal mantiene 
el programa en ejecución hasta que el usuario decida finalizarlo. 
Uso de estructuras de datos 
 Listas: Para almacenar los cursos y sus notas. 
 Colas: Simulan una lista de solicitudes de revisión de notas. 
 Pilas: Registran los cambios en las calificaciones (historial). 
Algoritmos de ordenamiento implementados 
Se implementaron dos algoritmos de ordenamiento principales: 
1. Burbuja (Bubble Sort): 
Usado para ordenar los cursos según la nota de menor a mayor. Es fácil de entender 
y suficiente para listas pequeñas. 
2. Inserción (Insertion Sort): 
Empleado para ordenar los cursos por nombre alfabéticamente. Es más rápido en 
listas pequeñas o casi ordenadas y mantiene la relación entre curso y nota. 
Documentación breve de funciones 
Función 
registrar_curso_lista() 
mostrar_cursos_lista() 
Descripción 
Permite agregar nuevos cursos y sus notas. 
Muestra todos los cursos registrados. 
promedio() 
Calcula el promedio general de todas las notas. 
cursos_aprobados_reprobados() Clasifica los cursos en aprobados y reprobados 
según la nota mínima (61). 
buscar_curso() 
actualizar_nota() 
borrar_curso_lista() 
ordenar_por_nota_burbuja() 
Busca un curso usando búsqueda lineal. 
Actualiza la nota de un curso existente y guarda el 
cambio en la pila. 
Elimina un curso de la lista. 
Ordena los cursos por nota. 
ordenar_por_nombre_insercion() Ordena los cursos alfabéticamente. 
buscar_curso_binario() 
simular_cola_revision() 
mostrar_historial() 
Realiza búsqueda binaria en una lista ordenada. 
Gestiona solicitudes de revisión de notas. 
Muestra los cambios registrados en la pila.

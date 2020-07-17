 ~~~
 This is a coding example working on IRIS 2020.1 and on Caché 2018.1.3 
 It will not be kept in sync with new versions      
 It is also NOT serviced by InterSystems Support !   
~~~ 

Esto se refiere a la última actualización ya SUDOKUes.mac 
  
     ;; ¡Bienvenido a esta demostración de SUDOKU!
     ;; puedes resolver tu SUDOKU más fácilmente o crear el tuyo propio
     ;; debajo de cada casilla encontrará una lista
     ;; de valores permitidos para este cuadro
     ;; complete los números 1..9 según lo necesite
     ;; para borrar una casilla, introduzca cualquier caracter o espacio en blanco
     ;; para parar, introduzca . o , para resolver, introduzca ?
     ;; puede navegar entre las casillas con las teclas <>^v
     ;; comandos de administración simples:
     ;; . para parar
     ;; , para parar
     ;; * iniciar el solucionador
     ;; x eXportar estado real a csv_file (0 = terminal)
     ;; i importar el estado de csv_file (0 = terminal)
     ;; ^ escribir instantánea en el cuadro global ^
     ;; ! cargar instantánea desde el cuadro global ^
     ;;
     ;; Para una mejor visualización, necesita un terminal configurado a 48x80
     ;;
Adelante:

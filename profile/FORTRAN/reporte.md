programa 1-loop-intech.f90
se aplicaron opciones de obtimizacion -O0 (a) -O1(b) y -O3(c):
si corremos time/01_loop_intech.f90
el tiempo pasa de 1.315 1.23 a  0.43 para (a),(b) y (c), respectivamente
que redujo el tiempo hasta el 70% en el caso de -O3
se aplico prof:
-el tiempo pasa de 1.30 a 1.22 a 0.37 para (a), (b) y (c), respectivamente 
programa 2-gprof-ex.f90
time/01_loop_intech.f90
 el tiempo pasa de 3.42 a 0.02 a 0.02 para (a), (b) y (c), respectivamente 
 se aplico prof:
lo primero que vemos es que se hacen mas llamadas a funciones ademas del main
el tiempo pasa de 1.88 a 0.98 a 0.88 para (a), (b) y (c), respectivamente 

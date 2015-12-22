# Fiches_n_cheats
Useful commands, scripts and more

1/ Correction tools :

Debug and find leaks:

run -> valgring --leak-check=full ./a.out a.out_args
 
Leaks only :

run -> a.out (must run indefinitely)

run -> ps

   do -> find executable's PID
   
run -> leaks PID

List functions used by an executable (system functions are marked as U, project-specific functions are marked as T) :

run -> nm -g ./a.out

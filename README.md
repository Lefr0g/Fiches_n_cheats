# Fiches_n_cheats
## Useful commands, scripts and more

### Correction tools

#### Debug and find leaks
```
valgring --leak-check=full ./a.out a.out_args
```
#### Leaks only
Notice that the tested program must run indefinitely to keep an active PID
```
a.out
ps
```
Then find executable's PID
```
leaks PID
```
#### List functions used by an executable
Great for finding forbidden functions.
System functions are marked as U, project-specific functions are marked as T
```
nm -g ./a.out
```

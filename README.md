# Fiches_n_cheats
## Useful commands, scripts and more

### Correction tools

#### Debug and find leaks
```
valgring --leak-check=full ./a.out a.out_args
```
#### Leaks only
```
a.out (must run indefinitely)

ps
```
find executable's PID
```
leaks PID
```
#### List functions used by an executable (system functions are marked as U, project-specific functions are marked as T)
```
nm -g ./a.out
```

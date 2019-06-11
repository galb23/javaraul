# comandos consola
> notas tmux es un multiplexor de terminal para sistemas tipo unix
1. para abrir tmux se utilza el siguiente comando:
```shell
tmux
```
2. para ver el listado de terminales tmux se utiliza

```shell
  tmux ls
```
![representacion grafica de un cambio de estado ](imagenes/tmuxls.PNG)

3. para reingresar a una terminal de tmux que esta abierta
```shell
  tmux attach-session -t [nombre de la session]
```

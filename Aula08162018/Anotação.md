Redes 
===

* Troca de informações 
* Compartilhamento de 
    - software
    - hardware

Ponto-a-Ponto
---

```
pc        pc
 *--------*
```

Cliente-servidor
---

``` 
sv
*-----------|--*cli
            |--*cli
            |--*cli
```
Barramento
---

```
|--------------------------|
    |       |       |
    *cli    *cli    *cli

```   


Anel (token ring)
---

```
                  ->        
              |-----------|
       cli*---|           |---*cli
              |           |
       cli*---|           |---*cli
              |-----------|
                  <-
```

Estrela
---

```


        cli*           *cli
            \         /
            |---------| <---- concentrador
            |---------|
            /         \
        cli*           *cli
                  
```

Hibrida
---

```

|------------------------|
    |       |       |
    *cli    *cli    |
                    |
                    |
               ->   |
              |-----------|
       cli*---|           |---*cli
              |           |
       cli*---|           |---*cli
              |-----------|
                   |     <-
                   |                    
        cli*       |   *cli
            \      |  /
            |---------| <---- concentrador
            |---------|
            /         \
        cli*           *cli
```

Malha
---

```

x---x
|\ /|
| x |
|/ \|
x---x

```
|   |definição|Área de uso|Público-alvo|hardware comum|
|---|---|---|---|---|
|pan|personal area network|-casa<br>-loja|usuario domestico|-roteador|
|laj|local|-escola<br>-comercio<br>-empresa|trabalhadores|-servidor<br>-switch|
|man|metropolitan|-orgãos pref.<br>-matriz/filial|trabalhadores<br>estudantes|-antenas<br>-fibra ópticas<br>-roteadores empres.|
|wan|wide|-internet|"<br>"|-idem a man<br>-satélite|
|san|storage|-|-|mainframe|
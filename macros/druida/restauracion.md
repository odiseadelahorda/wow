# Druida - Restauración



#### `Acechar`

* Independientemente de la forma actual en la que te encuentres, quedarás en forma felina y en sigilo

```
#showtooltip
/cancelform [noform:2]
/cast Acechar
```



#### `Alivio presto` o `Alivio presto` + `Resguardo de Cenarius` ambos con overmouse

* Al ubicar el ratón sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutará `Alivio presto` o `Resguardo de Cenarius`.
* Al tener seleccionado un jugador aliado, ejecutará `Alivio presto` o `Resguardo de Cenarius`.
* En cualquier otro caso, ejecutará `Alivio presto` o `Resguardo de Cenarius` sobre ti.

```
#showtooltip
#showtooltip Alivio presto
/castsequence [@mouseover,help,nodead,talent:1/2][help,nodead,talent:1/2][@player,talent:1/2] reset=29 Alivio presto, Resguardo de Cenarius
/cast [@mouseover,help,nodead][help,nodead][@player] Alivio presto
```

> Es interesante cambiar el orden de ejecución de `Alivio presto` y `Resguardo de Cenarius` si tienes el legendario [Edraith](http://es.wowhead.com/item=137095/edraith-ataduras-de-aglaya&spec=105) para realizar un `Resguardo de Cenarius` un 120% más fuerte.



#### `Cura de la Naturaleza` con overmouse

* Al ubicar el ratón sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutará `Cura de la Naturaleza`.
* Al tener seleccionado un jugador aliado, ejecutará `Cura de la Naturaleza`.
* En cualquier otro caso, ejecutará `Cura de la Naturaleza` sobre ti.

```
#showtooltip
/use [@mouseover,help,nodead][help,nodead][@player] Cura de la Naturaleza
```



#### `Rejuvenecimiento` con overmouse o `Fuego solar`

* Al ubicar el ratón sobre un jugador aliado o sobre una barra de salud aliada del interfaz, ejecutará `Rejuvenecimiento`.
* Al tener seleccionado un jugador aliado, ejecutará `Rejuvenecimiento`.
* Al tener seleccionado un enemigo, ejecutará `Fuego solar(Solar)`.
* En cualquier otro caso, ejecutará `Rejuvenecimiento`.

```
#showtooltip
/use [@mouseover,help,nodead][help,nodead] Rejuvenecimiento
/use [harm] Fuego solar(Solar); Rejuvenecimiento
```

> Con esta macro puedes sacarte todos los hechizos de daño bindeados a curas
>
> Es muy interesante si tienes el legendario [Promesa de Elune](http://es.wowhead.com/item=137023/promesa-de-elune-diosa-de-la-luna&spec=105) (De Equilibrio) bindearte también  `Cólera Solar` a algún hechizo (Recomiendo a `Toque de sanación` debido que llegarás a disparar alguna que otra sanación pensando que estás atacando y este hechizo es el que menos maná consume)










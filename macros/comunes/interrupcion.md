# General



## `Interrupción`

* Ejecuta el hechizo INTERRUPCION sobre el foco establecido, en caso de no existir un foco establecido ejecutará la interrupción sobre el objetivo seleccionado.
* Escribe en el chat /say un mensaje informando del objetivo al cual se le ha ejecutado el hechizo INTERRUPCION

```
#showtooltip
/use [@focus,exists,nodead][] INTERRUPCION
/run local m, _, u = "Corto en %s", SecureCmdOptionParse"[@focus]" if u then SendChatMessage(m:format(UnitName(u) or "Corto en %t")) end
```

> Es necesario reemplazar la cadena de texto "INTERRUPCION" por el nombre del hechizo que realice el corte para que la macro funcione. Por ejemplo, Testazo, Zurrar, etc.
# Druida - Comunes

## Forma de buhogato (Aspecto secreto feral)

Para conseguir el aspecto de buhogato deberás encontrar tres piedras que pueden salir en las siguientes ubicaciones. Con esta macro sabrás en qué territorios tienes activo el evento.

```txt
/script for q,i in pairs({["Event"]=44326,["Feralas Act"]=44327,["Hinter Act"]=44328,["Dusk Act"]=44329,["Feralas Tou"]=44331,["Hinter Tou"]=44332,["Duskwood Tou"]=44330})do print(q,IsQuestFlaggedCompleted(i))end
```
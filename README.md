# Aers... Code
## 🇨🇱 Los `spinnerVerbs` de Claude Code versión Chileno



> "...si igual tenís que esperar a que cargue...
> ríete un poco."


Aers... Code 
es un poquito de humor que se me ocurrió después de leer un millón de veces esas palabras raras que muestra Code. 
Algunas divertidas otras no tanto y pensé... 

¿y si le pongo un PPQL aqui? 

y aquí estamos...


*No acelera a Claude*

*No mejora los prompts*

*No arregla los bugs*


El pack `aers.json` te permite agregar o cambiar los verbos que usa Code mientras piensa o lo mandas a hacer una tarea. 
No hay ninguna lógica especial, ni detección de contexto ni nada. Solo un reemplazo o suma. (Sería interesante saber si es que eso se puede detectar, pal TODO.md)


## Instalación:

Escoje desde la carpeta packs/ ~~alguno de los packs de frases~~ aers.json que te comparto, y reemplaza o agrega a tu archivo de `settings.json` que se encuentra en la carpeta `.claude/` según lo que desees hacer con los verbos originales:

`"mode": "append"` = para agregar nuevas frases y mantener los verbos originales (Seleccionado por omisión)

`"mode": "replace"` = para reemplazar los originales por los de ~~los packs~~ aers.js .

```json
{
  "spinnerVerbs": {
    "mode": "append",
    "verbs": [
      "Tomándose un cafecito...",
      "Buscando el condoro...",
      "¿De dónde chucha lo forkiee?..."
    ]
  }
}
```


`Solo hace un poco más entretenidos esos segundos en que no se qué está pasando pero va.`


#### Fuente
[Documentación de Claude Code by Anthropic - Settings](https://code.claude.com/docs/en/settings)

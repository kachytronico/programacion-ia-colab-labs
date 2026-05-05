# Guía para trabajar con Google Colab

## Cómo abrir un notebook desde GitHub en Colab

Hay dos formas principales:

### Opción 1: Badge "Open in Colab"

Cada notebook publicado incluirá un badge en su README. Haz clic en él para abrirlo directamente en Colab.

### Opción 2: URL manual

Usa este patrón de URL:

```
https://colab.research.google.com/github/<usuario>/<repositorio>/blob/<rama>/<ruta-al-notebook>.ipynb
```

Ejemplo para este repositorio:

```
https://colab.research.google.com/github/kachytronico/programacion-ia-colab-labs/blob/main/notebooks/01_energy_economics_clustering/energy_economics_clustering.ipynb
```

## Cómo añadir un badge "Open in Colab"

Añade este markdown al README del notebook o al propio notebook:

```markdown
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/kachytronico/programacion-ia-colab-labs/blob/main/notebooks/<carpeta>/<nombre>.ipynb)
```

Sustituye `<carpeta>` y `<nombre>` por los valores reales.

## Flujo de trabajo recomendado

1. **Trabajar en Colab**: desarrolla y prueba el notebook en Google Colab.
2. **Guardar una copia en GitHub**: desde Colab, usa `Archivo > Guardar una copia en GitHub` o descarga el `.ipynb` y súbelo manualmente al repositorio.
3. **Revisar los outputs**: antes de hacer commit, revisa que los outputs sean útiles y no contengan información privada.
4. **Actualizar los enlaces README**: actualiza el badge "Open in Colab" en el README del notebook y en el README principal.
5. **Mantener las explicaciones claras**: asegúrate de que las celdas de texto del notebook explican el razonamiento, no solo el código.

## Notas sobre renderizado

- **GitHub** renderiza los notebooks de forma estática (puedes ver el código y las salidas guardadas, pero no ejecutarlos).
- **Google Colab** permite ejecutar el notebook directamente en la nube, con acceso a GPU/TPU si es necesario.
- Para ver notebooks actualizados, puede ser necesario recargar la página en GitHub, ya que el renderizado puede estar cacheado.

## Consejos

- Limpia los outputs antes de hacer commit si son muy grandes o contienen información privada.
- Añade celdas de texto (Markdown) para explicar cada sección del notebook.
- Documenta la fuente y condiciones de uso del dataset en la primera sección del notebook.
- Indica qué versiones de las bibliotecas principales estás usando si son relevantes para reproducir resultados.

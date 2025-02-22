### **Ejercicios de CSS**

Estos ejercicios consisten en una serie de tareas relacionadas con **CSS**, diseñadas para complementar el contenido de **HTML y CSS** en The Odin Project (**TOP**). **Deben completarse únicamente cuando se indique durante el curso del plan de estudios**.

Al realizar estos ejercicios, usa toda la documentación y los recursos que necesites para completarlos. **No se espera que memorices nada en este punto**. Consulta la documentación, usa Google y haz lo que necesites (excepto revisar las soluciones antes de tiempo) para resolverlos.

> [!IMPORTANTE]  
> Te animamos a practicar tus habilidades en Git realizando **commits** de tus cambios y subiéndolos a tu propio *fork*. Sin embargo, por favor **NO** abras un **Pull Request** para fusionar tus soluciones en este repositorio ni para mostrar tus respuestas.  
> Si fusionáramos los cambios, los ejercicios dejarían de estar disponibles como se diseñaron para los nuevos estudiantes. Además, abrir un **PR** solo genera trabajo adicional para nosotros, ya que tendremos que cerrarlo sin fusionarlo.

---

## **Contribuciones**

Si tienes **sugerencias** para mejorar un ejercicio, **ideas** para nuevos ejercicios o detectas un **problema** con alguno, puedes abrir un **issue** después de leer detenidamente nuestra [guía de contribución](https://github.com/TheOdinProject/.github/blob/main/CONTRIBUTING.md).

---

## **Cómo usar estos ejercicios**

1. **Haz un *fork* y clona este repositorio**.  
   Para aprender cómo hacer un *fork* de un repositorio, consulta la documentación de GitHub sobre cómo [hacer un *fork*](https://docs.github.com/en/get-started/quickstart/fork-a-repo).  
   - Las copias de repositorios en tu computadora se llaman *clones*. Si necesitas ayuda para clonar un repositorio en tu entorno local, puedes aprender cómo hacerlo en la documentación de GitHub sobre [clonar un repositorio](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
   
2. **Ve al directorio de un ejercicio y abre el archivo HTML en un navegador**.  
   Puedes abrir el archivo directamente o utilizar herramientas como la extensión **Live Server** de VS Code.

3. **Lee cuidadosamente el README antes de empezar**.  
   - Cada README incluye una lista de **"Self Check"** (*Verificación propia*). Usa esta lista para asegurarte de no haber pasado por alto ningún detalle importante.

4. **Realiza las modificaciones necesarias en `index.html` y/o `style.css`** para que el resultado en tu navegador se parezca a la imagen de **"Resultado Deseado"**.  
   - Dependiendo de las instrucciones del ejercicio, puede que solo necesites modificar uno de estos archivos.

5. **Cuando termines un ejercicio, compara tu solución con la de The Odin Project**.  
   - No revises la solución hasta que hayas terminado.  
   - Si tu solución es muy diferente a la de **TOP**, pero aún cumple con los requisitos del ejercicio, ¡no hay problema! Si tienes dudas, puedes preguntar en nuestro **Discord**.

> [!IMPORTANTE]  
> **No envíes tus soluciones a este repositorio**, ya que cualquier **Pull Request** con soluciones será cerrada sin fusionarse.

---

## **Algunas pistas**
- Las soluciones oficiales colocan todos los cambios **al final** del archivo CSS. Esto puede generar duplicados en los selectores (por ejemplo, puede haber un `body {}` en el CSS dado y otro `body {}` en la solución).  
  **Cuando trabajes en un ejercicio, es mejor práctica agregar tu CSS a los selectores existentes en lugar de duplicarlos al final del archivo**.  
  En las soluciones oficiales se sacrifica esta práctica para que sea más claro qué cosas se modificaron para resolver el ejercicio.

- **No te preocupes por valores exactos de píxeles** para márgenes, rellenos y tamaños de fuente, **a menos que se mencione en la sección de verificación propia**.  
  Estos ejercicios están diseñados para probar tu conocimiento de **CSS**, **no** tu capacidad de adivinar si una captura de pantalla usa `font: sans-serif bold 16px` o si un margen mide exactamente `42px`.

- Puede que necesites **agregar elementos a tu HTML** para colocar las cosas en el lugar correcto. *(En los primeros ejercicios, esto se menciona explícitamente cuando es necesario).*

- Es posible que debas **agregar más selectores** en tu archivo CSS.  
  En los primeros ejercicios, casi todo está preparado para ti, pero a medida que avances, notarás que debes agregar más y más selectores para obtener el resultado correcto.



************************************************************************************************************************************************************************

# CSS Exercises
These exercises consist of a series of CSS-related tasks intended to complement the HTML and CSS content on The Odin Project (TOP). They should only be completed when instructed during the course of the curriculum.

When doing these exercises, please use all documentation and resources you need to accomplish them. You are _not_ intended to have any of this stuff memorized at this point. Check the docs, use Google, and do what you need to do (besides checking the solutions) to get them done.

> [!IMPORTANT]
> We encourage you to practice your git skills by committing your changes and pushing them to your own fork.  However, please **DO NOT** open a Pull Request to have your solutions merged into this repo or to show your solution.  If we were to merge your changes the exercises would no longer be available as intended for new learners, and opening a PR only causes additional work for us, as we have to close it without merging.

## Contributing

If you have suggestions to improve an exercise, ideas for a new exercise, or notice an issue with an exercise, please feel free to open an issue after thoroughly reading our [contributing guide](https://github.com/TheOdinProject/.github/blob/main/CONTRIBUTING.md).

## How To Use These Exercises

1. Fork and clone this repository. To learn how to fork a repository, see the GitHub documentation on how to [fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo).
    - Copies of repositories on your machine are called clones. If you need help cloning to your local environment, you can learn how from the GitHub documentation on [cloning a repository](https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository-from-github/cloning-a-repository).
1. Go to an exercise directory and open the HTML file in a web browser. You can open the file directly or use something like VSCode's Live Server extension.
1. For each exercise, read the README thoroughly before starting any work.
    - Each README has a "Self Check" list. Use this to ensure you haven't missed any important details in your implementation.
1. Make your edits in the `index.html` and/or the `style.css` files in order to make the output in your browser look like the Desired Outcome image(s).
    - Depending on the instructions of the exercise, you may only need to make edits in one of these files.
1. Once you successfully finish an exercise, check TOP's solution to compare it with yours.
    - You should not be checking the solution for an exercise until you finish it!
    - If your solution differs wildly from TOP's solution (and still passes the exercise's requirements), that's completely fine. Do feel free to ask about it in our Discord if there are parts you do not understand.

> [!IMPORTANT]
> Do not submit your solutions to this repo, as any PRs that do so will be closed without merging.

## Some Hints
- The official solutions put all changes at the _end_ of the CSS file, which may duplicate some selectors (e.g. there might be a `body {}` in the given CSS and another `body {}` in the solution). When you are working on an exercise, it is best practice to add your CSS to existing selectors instead of duplicating them at the end of the file. We're sacrificing this best practice in our official solutions to make it extra clear to you what things we changed to solve the exercise.
- Unless listed in the self-check section, do not worry about getting the exact pixel value for things like margin, padding and font size. These exercises are intended to test your knowledge of CSS, not your ability to guess that a screenshot is using `font: sans-serif bold 16px` or that the margin is _exactly_ `42px`.
- You may need to add some elements to your HTML to get things into the right spot. (For the first few exercises, we make it explicit when this needs to happen.)
- You may need to add more selectors to your CSS file. The first few exercises have almost everything already done for you, but as you progress, you'll find that you need to add more and more selectors to get the correct result.

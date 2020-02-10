# How to Contribute

## Add a New Notebook

---

Before proposing a new notebook to be added, ensure the following

- It is not a duplicate or very similar to another notebook. If it is, consider collaborating with the other author to merge the code into a single notebook.
- Make sure it has been tested and can run on [Colaboratory](https://colab.research.google.com/).
- If the example requires a dataset, make sure it is hosted and can be downloaded with `wget` or `curl` from the notebook.

When you are ready to submit a new Notebook

1. Give the file a descriptive and concise name that uses [snake case](https://en.wikipedia.org/wiki/Snake_case)
1. Add the Colab and GitHub buttons with the following snippet with the updated paths:

   ```html
   <table class="tfo-notebook-buttons" align="center">
     <td>
       <a
         target="_blank"
         href="https://colab.research.google.com/github/notebookexplore/notebookexplore/blob/master/<CATEGORY>/<FRAMEWORK - pytorch | tensorflow | other>/<FILE NAME>.ipynb"
         ><img src="https://www.tensorflow.org/images/colab_logo_32px.png" />Run
         in Google Colab</a
       >
     </td>
     <td>
       <a
         target="_blank"
         href="https://github.com/notebookexplore/notebookexplore/blob/master/<CATEGORY>/<FRAMEWORK - pytorch | tensorflow | other>/<FILE NAME>.ipynb"
         ><img
           src="https://www.tensorflow.org/images/GitHub-Mark-32px.png"
         />View source on GitHub</a
       >
     </td>
   </table>
   ```

1. Add license and credit as the last section of the notebook
1. Submit a PR using the [Add Notebook template]()

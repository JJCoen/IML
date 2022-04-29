# Interpretable-ML-Models

A [workflowr][] project.

[workflowr]: https://github.com/workflowr/workflowr

Prior to running the analysis notebooks and updating the research website, at least a cursory knowledge of `workflowr` is necessary.

If one only wants to run the analysis files, then all of the rmarkdown and jupyter python notebooks are in the `code` subdirectory.  Please set the working directory for RStudio to the `code` subdirectory in order to run the .Rmd files.  Similarly, open Jupyter in the `code` directory and run the .IPYNB files from there.  The only exception is the AIX 360 Python notebook, which needs the colab runtime in order to execute.  Access to this is via the `workflowr` website.

To view the `workflowr` research website, set the working directory to the project directory (`Interpretable-ML-Models`).  Ensure that the `workflowr` package has been installed and load the `workflowr` library.  At the console, issue the command:
> workflow_view()

This will display the website in the Viewer.  To see the full scope of the website, select the 'show in new window' button (within the Viewer tab).

Alternatively, the easiest way to view the website is through the internet by entering the following URL in the address bar:
https://jjcoen.github.io/Interpretable-ML-Models/


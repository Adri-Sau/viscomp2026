# [viscomp2026](https://vlg.inf.ethz.ch/teaching/Visual-Computing.html)

GitHub repository for the Visual Computing course 2026 at ETH Zurich.

## Requirements for the Vision Part

- [Python 3](https://www.python.org/downloads/)
- [JupyterLab](https://jupyter.org/install)
- NumPy and Matplotlib

Clone this repository and open the exercise notebooks from the corresponding folder under `Exercises/`.

### Google Colab

The vision notebooks can also run in [Google Colab](https://colab.research.google.com/), without a local Python installation.

For Exercise 1, open the notebook directly in Colab:

[![Open Exercise 1 in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tavisualcomputing/viscomp2026/blob/main/Exercises/W2/week2_digital_image_student.ipynb)

The notebook downloads its accompanying image from this repository when the file is not already available locally.

Alternatively, in Colab select **File > Open notebook > GitHub** and enter:

`https://github.com/tavisualcomputing/viscomp2026`

## Requirements for the Graphics Part

We highly recommend using Visual Studio Code for solving the exercises, though you are free to choose any IDE.

To see the output of your code while solving the exercises, please follow one of the steps below:

- **VS Code:** Install the `vscode-preview-server` extension. Right-click the `.html` file and select either **Launch on browser** or **Preview on side panel**.
- **Python 3:** In the directory containing the `.html` file, run `python -m http.server`. Then open [http://localhost:8000](http://localhost:8000) in your browser. You can choose another port by adding it to the command.

Some browsers or versions may not be supported. Please check the WebGL initialization code in the respective exercise or ask us during the exercise sessions.

For syntax highlighting in Visual Studio Code, we recommend the **WebGL GLSL Editor** extension.

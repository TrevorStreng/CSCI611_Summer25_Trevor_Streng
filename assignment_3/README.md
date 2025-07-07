# Assignment 3

## Style Transfer

This is a project that takes in two images, one for content and the other for style. It takes the content of one image and applies the style of the other image. It uses a pretrained neural network called vgg and only updates the pixels of the output image and not any weights of the network.

## Requirements

This project is written in Python and uses the Jupyter notebook.

Install Python and Anaconda(optional)

## Versions I Used

filelock 3.18.0
fsspec 2025.5.1
Jinja2 3.1.6
MarkupSafe 3.0.2
mpmath 1.3.0
networkx 3.5
numpy 2.3.1
pillow 11.3.0
pip 24.0
setuptools 80.9.0
sympy 1.14.0
torch 2.7.1
torchvision 0.22.1
typing_extensions 4.14.1

I used vscode for all of my text editing and testing

## Steps

<ol>
  <li>clone repo from github</li>

```
git clone https://github.com/TrevorStreng/CSCI611_Summer25_Trevor_Streng.git
```

  <li>cd assignment_3</li>

  <li>Set up virtual environment(optional)</li>
  <ol>
    <li>python -m venv venv</li>
    <li>venv\Scripts\activate</li>
  </ol>

  <li>pip install torch torchvision</li>

  <li>run all</li>

</ol>

### Weights you adjust to change style to content ratios.

<ul>
  <li>content_weight</li>
  <li>style_weight</li>
  <li>style_weights</li>
  <li>lr (learning rate)</li>
  <li>steps</li>
</ul>

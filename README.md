Tired of reading dependency structures as text in your jupyter
notebook?  This jupyter notebook extension visualizes NLP output using
brat[^1], encapsuled by annodoc[^2].

## Installation
```sh
git clone --recurse-submodules https://github.com/Marny30/jupyter-annodoc
jupyter nbextension install jupyter-annodoc --user
jupyter nbextension enable jupyter-annodoc
```

## How to use
Example input (see [^2] for more examples)
```txt
~~~ ann
Barack Obama is the current president.
T1 PERSON 0 12 Barack Obama
~~~
```
Output the above string and clic on the button provided by this extension to convert into a brat visualization.

----

This fork implements the support of all types (ann, conllu, conllx, sdparse) provided by Annodoc. Because of current annodoc's restriction, only single-lined inputs are accepted except for sdparse. All credits do to its author. 



[^1]: http://brat.nlplab.org/
[^2]: http://spyysalo.github.io/annodoc/

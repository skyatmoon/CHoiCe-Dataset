# Cursive-Handwriting-Dataset
A Cursive Handwriting Dataset with 62 classes cursive handwriting letters, "0-9, a-z, A-Z",\
each class at least have 40 pictures,the data is still updating

Here are Original data examples     and           Binary data examples:\
![](1.png)                            ![](2.png)

Data mostly comes form Professor Tom's own handwritting and partly from CEDAR free handwriting pages.

in V0.2/dada is the 28 x 28 original handwriting letters\
in V0.2/data-bin is the 28 x 28 binary handwriting letters

Thanks to:
* Prof. Tom Gedeon  tom@cs.anu.edu.au
* CEDAR dataset: https://cedar.buffalo.edu/handwriting/HRdatabase.html 

## Data set browsing

*<u>"The data of the dataset is collected from Professor Tom Gedeon and the complete handwriting paper of the CEDAR handwriting dataset. The data format is a 28x28 ".png" format picture. The data set has a total of sixty-two categories of 0-9, a-z and A-Z, corresponding to the files "data (1)" to "data (62)" in the order of "label.txt". The data set is divided into two parts, the unprocessed original data image is stored in the "data (1)" to "data (62)" in the "V0.2/data" folder, and the binarized data image Stored in "data (1)" to "data (62)" in the "V0.2/data-bin" folder."</u>*

#### Data statistics


![](3.png) 

#### File Sturcture

*<u>"use follwing template or '[tree](https://www.tecmint.com/linux-tree-command-examples/)' command in linux"</u>*

```reStructuredText
the project
 |
 +--+v0.2                    #include all data in the dataset, youcan see each .png data on the page
 |  |
 |  +---data                 #include all general rgb data
 |  |  |
 |  |  |
 |  |  +---data (1)          # class "0"
 |  |  …                     # the whole 62 classes of the data set, 0-9, a-z,A-Z
 |  |  |
 |  |  +---data (62)         # class "Z"
 |  +---data-bin             # include all binary data of their rgb origin
 |  |  |
 |  |  |
 |  |  +---data (1)
 |  |  …
 |  |  |
 |  |  +---data (62)
 |  +---label.txt            # labels from "data (1)" to "data (62)"
 +--v0.2.zip                 # the .zip file for the whole dataset
```


------

### Cite the Paper

Use the following bibtex for citing the paper: 

```reStructuredText
@...

```

The BERBER-MNIST Dataset
========================

What is it?
-----------
The BERBER-MNIST Dataset is a set of handwritten uppercase character derived from the EMNIST Dataset and **compatible with the MNIST dataset**. 

The compatibility of this dataset with the MNIST paradigm. makes its easy to use and without changing your algorithms. Also not even necessary the understanding of Berber scripting.

Formats
-------
The dataset is provided in .csv format.


**Latin-version** : A,Ԑ,B,C,Č,D,Ḍ,E,F,G,Ǧ,H,Ḥ,I,J,K,L,M,N,Q,Γ,R,Ṛ,S,Ṣ,T,Ṭ,TT,U,W,X,Y,Z,Ẓ

**Tifinagh-version** : ⴰ,ⴱ,ⵛ,ⴷ,ⴹ,ⵄ,ⴼ,ⴳ,ⵖ,ⴳⵯ,ⵀ,ⵃ,ⵊ,ⴽ,ⴽⵯ,ⵍ,ⵎ,ⵏ,ⵇ,ⵔ,ⵕ,ⵙ,ⵚ,ⵜ,ⵟ,ⵡ,ⵅ,ⵢ,ⵣ,ⵥ,ⴻ,ⵉ,ⵓ

You can convert .csv file into images .png format using the following python notebook script: *csv2png.ipynb*.

Dataset Summary
---------------
There are two different version of Amazigh Script provided in this dataset. A short summary of the dataset is provided below:

| Latin-version          |   Tifinagh-version     |
|       ---              |      ---               |
| 247,985 characters     | 25,740 characters      |
| 33 unbalanced classes. | 33 unbalanced classes  |
|                        |                        |


Please refer to the BERBER-MNIST paper () for further details about Amazigh Script and the dataset structure.

How to cite
-----------
Please cite the following paper when using or referencing the dataset: 

Authors
-------
K. M.

_Centre de Recherche en Langue et Culture Amazigh_
_Bejaia, Algeria_

Email: k.muqran@gmail.com

Files
-----
The folder consists of the following files:

```bash
BERBER-MNIST 
│   Latin-version.csv
|   Tifinagh-version.csv   
|   csv2png.ipynb
│   README.md       

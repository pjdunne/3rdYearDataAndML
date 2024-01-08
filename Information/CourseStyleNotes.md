## Colours for different section types

<div style="background-color: #FFF8C6">
#### Optional, non-examinable




<div style="background-color:#FFCCCB">
#### Non-examinable mathematics




<div style="background-color:#C2F5DD">
#### Examples and exercises

<div style="background-color:#C2F5DD">

End of exercise


<div style="background-color: #C2D5BD"> 

OPTIONAL Exercise
 Also use EFS = Exercise for Student, for optional short mini-questions, prompts


<div style="background-color:#efdff2">
#### Appendices


## Internal hyperlinks

This trick for [internal hyperlinks](https://sebastianraschka.com/Articles/2014_ipython_internal_links.html)

```
[Text](#section2)

<a href='#section2'>Also sets a link</a>
```
Then you want TWO cells, first (perhaps with line)
```
<hr style="border:2px solid gray">
<a id='section2'></a>
```
then in next cell
`## Section 2` [^](#outline)






## Code snippet to set random seed

```
# Set the random seed for consistency. scipy.stats uses the numpy random number generator, so why not use 0?
np.random.seed(0)
```


# Colour blind friendly schemes from https://zenodo.org/records/3381072/files/Display_color_scales.R?download=1
# https://zenodo.org/records/3381072

Tol_bright = ['#EE6677', '#228833', '#4477AA', '#CCBB44', '#66CCEE', '#AA3377', '#BBBBBB']

Tol_muted = ['#88CCEE', '#44AA99', '#117733', '#332288', '#DDCC77', '#999933','#CC6677', '#882255', '#AA4499', '#DDDDDD']

Tol_light = ['#BBCC33', '#AAAA00', '#77AADD', '#EE8866', '#EEDD88', '#FFAABB', '#99DDFF', '#44BB99', '#DDDDDD']

#From Color Universal Design (CUD): https://jfly.uni-koeln.de/color/
Okabe_Ito = ["#E69F00", "#56B4E9", "#009E73", "#F0E442", "#0072B2", "#D55E00", "#CC79A7", "#000000"]



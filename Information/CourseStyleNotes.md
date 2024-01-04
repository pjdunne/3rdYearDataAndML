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
`## Section 2`






## Code snippet to set random seed

```
# Set the random seed for consistency. scipy.stats uses the numpy random number generator, so why not use 0?
np.random.seed(0)
```


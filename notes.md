
# to check 
---

- https://link.springer.com/article/10.1007/s00348-024-03915-9


# layout constrained matplotlib

https://matplotlib.org/stable/users/explain/axes/constrainedlayout_guide.html

basically this is what matter: 

_Constrained layout_ typically needs to be activated before any Axes are added to a figure. Two ways of doing so are

- using the respective argument to [`subplots`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html#matplotlib.pyplot.subplots "matplotlib.pyplot.subplots"), [`figure`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.figure.html#matplotlib.pyplot.figure "matplotlib.pyplot.figure"), [`subplot_mosaic`](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplot_mosaic.html#matplotlib.pyplot.subplot_mosaic "matplotlib.pyplot.subplot_mosaic") e.g.:
    
    [plt.subplots](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.subplots.html#matplotlib.pyplot.subplots "matplotlib.pyplot.subplots")(layout="constrained")
    

activate it via [rcParams](https://matplotlib.org/stable/users/explain/customizing.html#customizing-with-dynamic-rc-settings), like:
```plt.rcParams['figure.constrained_layout.use'] = True''' 
```
plt.rcParams['figure.constrained_layout.use'] = True''' pro
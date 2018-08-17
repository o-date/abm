# abm

[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/o-date/abm/master)

This binder uses the [Project Mesa](https://github.com/projectmesa/mesa) 'mesa' package for building and running agent based models. The sample notebooks are in the relevant model folders. They show how to build and run parameter sweeps. 

### For visualization run locally

 If you download this repository to your own computer, you can run the sample models and the visualizations -

```
 $ pip install -r requirements.txt
```

which should install everything you need. Change directory into one of the subfolders, and then

```
$ mesa runserver
```

which will open a new browser window at [http://127.0.0.1:8521/](http://127.0.0.1:8521/) and press Reset, then Run.


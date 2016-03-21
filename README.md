# openhouse

## Dependecies

* ipython
* reveal.js

## Preliminary

```
pip install ipython # if you not
npm install
```

## Usage

* Create and Edit `*.ipynb`
* Convert `*.ipynb` to slides and Deploy it to GitHub Page

### Create and Edit

```
ipython notebook YYYY.ipynb
```

e.g. `ipython notebook 2016.ipynb`

### Convert and Deploy

```
gulp deploy:gh-pages -y YYYY
```

e.g. `gulp deploy:gh-pages -y 2016`

Please check [here](http://sakai-lab.github.io/openhouse/).

## Thanks

* https://gist.github.com/hannes-brt/6207507

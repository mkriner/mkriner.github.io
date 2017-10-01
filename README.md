* To get this folder locally, run:
```
cd ~/git
git clone https://github.com/rasilab/rasidocs.git
```

* The presentation is written in [reveal.js](https://github.com/hakimel/reveal.js/).

* Create your slides in `svg` folder using [Inkscape](http://rasilab.org/ln/blog/2015/05/learning-manuals-for-commonly-used-lab-software/#Inkscape).

* To convert `svg` to `png` in batch, run following command from this folder:

```bash
for file in svg/*.svg; do inkscape -C -z --export-png="${file//svg/png}" "$file"; done
```

* Organize your slides by editing [index.html](index.html).

* View your presentation by opening [index.html](index.html) in a browser.

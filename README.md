# LifeQA

Code for the [LifeQA website](https://lit.eecs.umich.edu/lifeqa).

## Paper page thumbnails.

We used ImageMagick:

```bash
convert $PDF_FILE[0-6] -thumbnail x156 img/thumbs/%d.png
```

# sageiris.com

The website for Sage Iris, a calm home screen for Android, served by GitHub Pages at https://sageiris.com.

Everything here is built: the pages' source lives in the Sage Iris app repository, under `design/landing`,
and its `build.py` writes this folder:

```bash
python3 design/landing/build.py --out ../sageiris.com
```

Then commit and push here. Pages publishes the `main` branch as it is.

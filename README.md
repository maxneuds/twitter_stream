# twitter_stream

Twitter stream analyze project.

## settings

In folder `conf` create a settings file:

```
cd conf
mv settings.ini.example settings.ini
```

and fill in appropriate developer keys

```
[KEYS]
# consumer api keys
TWITTER_APP_KEY = abc
TWITTER_APP_SECRET = abc
# access token & secret
TWITTER_KEY = abc
TWITTER_SECRET = abc
```

## data pipeline

<img src="res/graph_pipeline.gv.png" alt="graph_pipeline" width="200"/>

<!--![graph_pipeline](res/graph_pipeline.gv.png)

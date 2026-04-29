# Express-Wani-Demo-Site

Static landing page for the proof-search profiling and visualisation
tool demonstrated on *wani* / *lightblue* (NALOMA VI 2026 archival
demo paper). The page embeds the live dashboard hosted at
`https://wani-viz-demo.fly.dev/searchlog`.

## Local preview

```sh
docker build -t wani-viz-site .
docker run -p 8080:80 wani-viz-site
open http://localhost:8080/
```

## Deploy (Fly.io)

```sh
fly apps create wani-viz-site
fly deploy
```

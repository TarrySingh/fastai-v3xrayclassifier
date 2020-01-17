An X-Ray classifier model built on fast-aiv3.

The model can, for now distinguish chest, foot and hand xrays...more to come.

The classifier web app is up at https://xrayclassifier-fastai.onrender.com/. Test it out with Xray images!

Test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 5000:5000 fastai-v3
```


#### How to build and execute

###### Clone repo
```
git clone https://github.com/lalatgithub/image-segmentation-using-scikit-image.git
```

###### Switch to project dir
```
cd image-segmentation-using-scikit-image
```

###### Create virtual env
```
python -m venv .venv
```

###### Activate virtual env
```
source .venv/bin/activate
```

###### Install dependencies
```
pip install -r requirements.txt
```

<img src="https://media.giphy.com/media/lGZCPXd5quy0xu9p3r/giphy.gif" width="400" height="400" />

###### Run project

Once the packages are installed. Run spyder IDE by running this from the same directory

```
spyder
```

Now hit the RUN button from the top toolbar in Spyder IDE and see the magic on right side of your IDE


##### What is this all about?

###### Segment an Image by Labeling image regions

This example shows how to segment an image with image labelling. The following
steps are applied:

1. Thresholding with automatic Otsu method
2. Close small holes with binary closing
3. Remove artifacts touching image border
4. Measure image regions to filter small objects

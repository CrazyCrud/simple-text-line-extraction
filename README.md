# Simple text line extraction

## Run
```
docker-compose up -d
```
To receive the unique token to access Jupyter run:
```
docker logs --tail 3 jupyter_text_line_extraction
```

## Implementation

You can extract baselines with [dhSegment](https://dhsegment.readthedocs.io/en/latest/).

To extract text line images the line height needs to be calculated which is done in the example code.

## TODO

- [ ] Include preprocessing step (baseline extraction)
- [ ] Include cropping the line images


You can change the number of classes of json file by using filter.py file

# Filter
filter.py allows you to filter an existing COCO Instances JSON file by categories.

The following command will filter the input instances json to only include images and annotations for the categories person, dog, or cat:
```python filter.py --input_json instances_train2017.json --output_json filtered.json --categories person dog cat```

Note: This isn't looking for images with all categories in one. It includes images that have at least one of the specified categories.

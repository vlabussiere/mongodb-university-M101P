# Retrieve the restaurants data
```
$ wget https://raw.githubusercontent.com/mongodb/docs-assets/primer-dataset/primer-dataset.json
```

# Import data into the collection
```
mongoimport --db test --collection restaurants --drop --file primer-dataset.json
```


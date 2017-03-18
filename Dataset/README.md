# Retrieve the restaurants data
```
$ wget https://raw.githubusercontent.com/mongodb/docs-assets/primer-dataset/primer-dataset.json
```

# Import data into the collection
```
mongoimport --db test --collection restaurants --drop --file primer-dataset.json
```

```
connected to: 127.0.0.1
2017-03-18T16:03:01.540+0100 dropping: test.restaurants
2017-03-18T16:03:04.009+0100 		Progress: 6523981/11874761	54%
2017-03-18T16:03:04.015+0100 			12100	4033/second
2017-03-18T16:03:06.081+0100 check 9 25359
2017-03-18T16:03:06.983+0100 imported 25359 objects
```

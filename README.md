Since Docker doesn't provide a really easy way of copying data out of named volumes (at least on
Mac, at least that I could find), this is a small project to do that.

Getting started is simple:

To build the Docker image:

```
make build
```

Then, assuming you have a volume named `notebooks` and a local directory named `target`, just
execute 

```
./extract-volume notebooks /full/path/to/target
```

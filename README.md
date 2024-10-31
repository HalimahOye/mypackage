# mypackage

## installing this package locally
'python setup.py sdist'

## installing mypackage from GitHub
'pip install git+<gitUrl>'

## updating mypackage from GitHub
'pip install ==upgrade git+<gitUrl>'

```install requires numpy
from mypackage import myModule

# returns [8,7,3]
myModule.top_n(([8, 3, 2, 7, 4], 3))

# returns [5, 4, 3, 2, 1]
myModule.top_n([1, 2, 3, 4, 5], 5)

# returns [12, 10]
myModule.top_n([10, 1, 12, 9, 2], 2)
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

"MIT"
Run the below command to build the library
```
$ zig build-lib -Doptimize=ReleaseSafe -dynamic recipe_book.zig
```

Run local web applicaton with writing this (PHP must be installed):
```
$ RECIPE_SO=<librecipe.so> php -S localhost:8080 -c ./php.ini
```

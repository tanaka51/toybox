# toybox

## requirements
* chef
* berkshelf
* knife-solo(if necessary)

## example

```sh
$ berks install --path cookbook
$ knife solo prepare target
$ knife solo cook target
```

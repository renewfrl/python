
# Challenge

* Use exercise22 as basis
* create a Hotel subclass which extends House and inherits automatically the methodes
* Create a new function which returns the type (in case hotel -> hotel)



The result should be then: 

```
hotel = Hotel('tesselschade', 1)
hotel.type # results in: 'hotel'
```

## Hit:

* extending a class is `subclass(class):`

* remember to call the `super()` method in the subclass

* to set a property you can use the @[name].setter

so

```
@door.setter
def door(self,x):
    this.door = x
   
```
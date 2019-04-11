```
class House:

    __housenumber = None
    __streetname = None
  
    def __init__(self, streetname, housenumber):
        self.__housenumber = housenumber
        self.__streetname = streetname
    
    @property
    def housenumber(self):
        return self.__housenumber
    
    @property
    def streetname(self):
        return self.__streetname
    
   
```
```

a = House()
print(a.housenumber)
print(a.streetname)
```
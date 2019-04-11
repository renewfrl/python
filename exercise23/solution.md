```
class House:

    __housenumber = 10
    __streetname = "Tesselschade"
    
    @property
    def housenumber(self):
        return self.__housenumber
    
    @property
    def streetname(self):
        return self.__streetname
    
    
```

a = House()
print(a.housenumber)
print(a.streetname)
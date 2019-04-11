```
class House:

    __housenumber = None
    __streetname = None
    __type = None
  
    def __init__(self, streetname, housenumber):
        self.__housenumber = housenumber
        self.__streetname = streetname
    
    @property
    def housenumber(self):
        return self.__housenumber
    
    @property
    def streetname(self):
        return self.__streetname
      
    @property
    def type(self):
        return self.__type
    
    @type.setter
    def type(self, x):
        self.__type = x

class Hotel(House):
    
    def __init__(self,streetname, housenumber):
        super().__init__(streetname, housenumber)
        self.type = 'hotel'
        self.hoi = 'hoi
   
   
```
```

a = Hotel('tesselschade', 1)
print(a.housenumber)
print(a.streetname)
print(a.type)
```
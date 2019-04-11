```
age_values = []
age = int(input("User 1: what is your age?: "))
age_values.append(age)
age2 = int(input("User 2: what is your age?: "))
age_values.append(age2)
age3 = int(input("User 3: what is your age?: "))
age_values.append(age3)
print("Min age: {} max age {} average age {}".format(max(age_values),min(age_values),mean(age_values)))
```

OR with nice formatting:

```
from statistics import mean
age_values = []
age = int(input("User 1: what is your age?: "))
age_values.append(age)
age2 = int(input("User 2: what is your age?: "))
age_values.append(age2)
age3 = int(input("User 3: what is your age?: "))
age_values.append(age3)
print("max age: {} min age {} average age {:.2f}".format(max(age_values),min(age_values),mean(age_values)))```
```

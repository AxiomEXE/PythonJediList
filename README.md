# PythonJediList
A Star Wars Themed Python Code

```

#!/usr/bin/python3

import random

jedi = ['Qui-Gon', 'Obi-Wan', 'Yoda', 'Mace Windu']
padawan = input('Future or Present?')
padawan = str(padawan)

if padawan == 'Present':
	print(jedi[0])
else:
	print(random.choice(jedi))


```

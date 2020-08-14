# Random-Numbers
import random
randomlist = []
for i in range(0,10):
    n = random.randint(1,500)
    randomlist.append(n)
print(sorted(randomlist))

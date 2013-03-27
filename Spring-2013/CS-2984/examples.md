Printing and Input
------------------
print('Hello, world!')
input("Prompt: ")

Power, Type, Casts
-------------------
3 to the 5th power:  (3 ** 5)
Type of 5: type(5)
Force Int: 3 // 5
Squareroot: 
  import math
  Math.sqrt
sum([1,2,3]) => 6
int(4.8) => 4

Strings
--------
'"hello" + "world" is: ', "hello" + "world"
  => ('"hello" + "world" is: ', "helloworld")
"%.4f -- %d -- %s" % (1/3, 78, "hello")
  => 0.3333 -- 78 -- hello
"one" * 2
  => "oneone"
"dopecat"[2]
  => 'p'
len("dopecat")
  => 7
"dopecat"[:5] or "dopecat"[0:5]
  => 'dopec'
"dopecat"[2:] => 'pecat'
"methbey".count('e')
  => 2
"hello".upper() 
  => "HELLO"
str(17)
  => "17"

Ranges
------
range(start,stop[,step])
range(1,11)
  => 1,2,3,4,5,6,7,8,9

Lists
-----
['a','b', 'C!!!'].append('d') => ['a', 'b', 'C!!!', 'd']
"el1,el2,el3".split(',') => ["el1", "el2", "el3"]
[i for i in range(1,11) if i%2 == 0] => [2,4,6,8]

Loops
-----
for i in range(1,10):
  print(i)
while condition:
  expressions

Conditionals
------------
if num % 2 == 0:
  print("It was even.")
elif true:
  print("this is the elif shit")
else:
  print("It was odd.")

Functions
---------
def dismiss(name):
  print("Get out of here, " + name + "!")

Random
------
import random
random.randint(1, 10)

URL Requests
------------
from urllib.request import urlopen
response = urlopen('http://ichart.finance.yahoo.com/table.csv?s=AAPL').read()
  .readlines() for []

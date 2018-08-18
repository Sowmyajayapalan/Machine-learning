# Machine-learning
ML code in Python by Sowmya - Basics
In [3]:
x=5
type(x)
Out[3]:
int
In [4]:
y=2.5
type(y)
Out[4]:
float
In [6]:
z = 1+2j
type(z)
Out[6]:
complex
In [7]:
(50-5*6)/4
Out[7]:
5.0
In [8]:
(50-5*6)//4
Out[8]:
5
In [9]:
7/3
Out[9]:
2.3333333333333335
In [11]:
from math import sqrt 
sqrt(81)
Out[11]:
9.0
In [12]:
import math
sqrt(81)
Out[12]:
9.0
In [14]:
math.sqrt(81)
Out[14]:
9.0
In [15]:
dir(math)
Out[15]:
['__doc__',
 '__loader__',
 '__name__',
 '__package__',
 '__spec__',
 'acos',
 'acosh',
 'asin',
 'asinh',
 'atan',
 'atan2',
 'atanh',
 'ceil',
 'copysign',
 'cos',
 'cosh',
 'degrees',
 'e',
 'erf',
 'erfc',
 'exp',
 'expm1',
 'fabs',
 'factorial',
 'floor',
 'fmod',
 'frexp',
 'fsum',
 'gamma',
 'gcd',
 'hypot',
 'inf',
 'isclose',
 'isfinite',
 'isinf',
 'isnan',
 'ldexp',
 'lgamma',
 'log',
 'log10',
 'log1p',
 'log2',
 'modf',
 'nan',
 'pi',
 'pow',
 'radians',
 'sin',
 'sinh',
 'sqrt',
 'tan',
 'tanh',
 'tau',
 'trunc']
In [16]:
!pip list
Package                            Version  
---------------------------------- ---------
alabaster                          0.7.10   
anaconda-client                    1.6.14   
anaconda-navigator                 1.8.7    
anaconda-project                   0.8.2    
asn1crypto                         0.24.0   
astroid                            1.6.3    
astropy                            3.0.2    
attrs                              18.1.0   
Babel                              2.5.3    
backcall                           0.1.0    
backports.shutil-get-terminal-size 1.0.0    
beautifulsoup4                     4.6.0    
bitarray                           0.8.1    
bkcharts                           0.2      
blaze                              0.11.3   
bleach                             2.1.3    
bokeh                              0.12.16  
boto                               2.48.0   
Bottleneck                         1.2.1    
certifi                            2018.4.16
cffi                               1.11.5   
chardet                            3.0.4    
click                              6.7      
cloudpickle                        0.5.3    
clyent                             1.2.2    
colorama                           0.3.9    
comtypes                           1.1.4    
conda                              4.5.4    
conda-build                        3.10.5   
conda-verify                       2.0.0    
contextlib2                        0.5.5    
cryptography                       2.2.2    
cycler                             0.10.0   
Cython                             0.28.2   
cytoolz                            0.9.0.1  
dask                               0.17.5   
datashape                          0.5.4    
decorator                          4.3.0    
distributed                        1.21.8   
docutils                           0.14     
entrypoints                        0.2.3    
et-xmlfile                         1.0.1    
fastcache                          1.0.2    
filelock                           3.0.4    
Flask                              1.0.2    
Flask-Cors                         3.0.4    
gevent                             1.3.0    
glob2                              0.6      
greenlet                           0.4.13   
h5py                               2.7.1    
heapdict                           1.0.0    
html5lib                           1.0.1    
idna                               2.6      
imageio                            2.3.0    
imagesize                          1.0.0    
ipykernel                          4.8.2    
ipython                            6.4.0    
ipython-genutils                   0.2.0    
ipywidgets                         7.2.1    
isort                              4.3.4    
itsdangerous                       0.24     
jdcal                              1.4      
jedi                               0.12.0   
Jinja2                             2.10     
jsonschema                         2.6.0    
jupyter                            1.0.0    
jupyter-client                     5.2.3    
jupyter-console                    5.2.0    
jupyter-core                       4.4.0    
jupyterlab                         0.32.1   
jupyterlab-launcher                0.10.5   
kiwisolver                         1.0.1    
lazy-object-proxy                  1.3.1    
llvmlite                           0.23.1   
locket                             0.2.0    
lxml                               4.2.1    
MarkupSafe                         1.0      
matplotlib                         2.2.2    
mccabe                             0.6.1    
menuinst                           1.4.14   
mistune                            0.8.3    
mkl-fft                            1.0.0    
mkl-random                         1.0.1    
more-itertools                     4.1.0    
mpmath                             1.0.0    
msgpack-python                     0.5.6    
multipledispatch                   0.5.0    
navigator-updater                  0.2.1    
nbconvert                          5.3.1    
nbformat                           4.4.0    
networkx                           2.1      
nltk                               3.3      
nose                               1.3.7    
notebook                           5.5.0    
numba                              0.38.0   
numexpr                            2.6.5    
numpy                              1.14.3   
numpydoc                           0.8.0    
odo                                0.5.1    
olefile                            0.45.1   
openpyxl                           2.5.3    
packaging                          17.1     
pandas                             0.23.0   
pandocfilters                      1.4.2    
parso                              0.2.0    
partd                              0.3.8    
path.py                            11.0.1   
pathlib2                           2.3.2    
patsy                              0.5.0    
pep8                               1.7.1    
pickleshare                        0.7.4    
Pillow                             5.1.0    
pip                                10.0.1   
pkginfo                            1.4.2    
pluggy                             0.6.0    
ply                                3.11     
prompt-toolkit                     1.0.15   
psutil                             5.4.5    
py                                 1.5.3    
pycodestyle                        2.4.0    
pycosat                            0.6.3    
pycparser                          2.18     
pycrypto                           2.6.1    
pycurl                             7.43.0.1 
pyflakes                           1.6.0    
Pygments                           2.2.0    
pylint                             1.8.4    
pyodbc                             4.0.23   
pyOpenSSL                          18.0.0   
pyparsing                          2.2.0    
PySocks                            1.6.8    
pytest                             3.5.1    
pytest-arraydiff                   0.2      
pytest-astropy                     0.3.0    
pytest-doctestplus                 0.1.3    
pytest-openfiles                   0.3.0    
pytest-remotedata                  0.2.1    
python-dateutil                    2.7.3    
pytz                               2018.4   
PyWavelets                         0.5.2    
pywin32                            223      
pywinpty                           0.5.1    
PyYAML                             3.12     
pyzmq                              17.0.0   
QtAwesome                          0.4.4    
qtconsole                          4.3.1    
QtPy                               1.4.1    
requests                           2.18.4   
rope                               0.10.7   
ruamel-yaml                        0.15.35  
scikit-image                       0.13.1   
scikit-learn                       0.19.1   
scipy                              1.1.0    
seaborn                            0.8.1    
Send2Trash                         1.5.0    
setuptools                         39.1.0   
simplegeneric                      0.8.1    
singledispatch                     3.4.0.3  
six                                1.11.0   
snowballstemmer                    1.2.1    
sortedcollections                  0.6.1    
sortedcontainers                   1.5.10   
Sphinx                             1.7.4    
sphinxcontrib-websupport           1.0.1    
spyder                             3.2.8    
SQLAlchemy                         1.2.7    
statsmodels                        0.9.0    
sympy                              1.1.1    
tables                             3.4.3    
tblib                              1.3.2    
terminado                          0.8.1    
testpath                           0.3.1    
toolz                              0.9.0    
tornado                            5.0.2    
traitlets                          4.3.2    
typing                             3.6.4    
unicodecsv                         0.14.1   
urllib3                            1.22     
wcwidth                            0.1.7    
webencodings                       0.5.1    
Werkzeug                           0.14.1   
wheel                              0.31.1   
widgetsnbextension                 3.2.1    
win-inet-pton                      1.0.1    
win-unicode-console                0.5      
wincertstore                       0.2      
wrapt                              1.10.11  
xlrd                               1.1.0    
XlsxWriter                         1.0.4    
xlwings                            0.11.8   
xlwt                               1.3.0    
zict                               0.1.3    
In [17]:
width = 20
length = 30
area = width * length
area
Out[17]:
600
In [22]:
height = 15
volume = area * height
volume
Out[22]:
9000
In [21]:
zoom
---------------------------------------------------------------------------
NameError                                 Traceback (most recent call last)
<ipython-input-21-d970bd78b2be> in <module>()
----> 1 zoom

NameError: name 'zoom' is not defined
In [25]:
import keyword
print(keyword.kwlist)
['False', 'None', 'True', 'and', 'as', 'assert', 'break', 'class', 'continue', 'def', 'del', 'elif', 'else', 'except', 'finally', 'for', 'from', 'global', 'if', 'import', 'in', 'is', 'lambda', 'nonlocal', 'not', 'or', 'pass', 'raise', 'return', 'try', 'while', 'with', 'yield']
In [26]:
return = 0
  File "<ipython-input-26-c7a05f6eb55e>", line 1
    return = 0
           ^
SyntaxError: invalid syntax
In [30]:
s = 'hello world'
print(type(s))
su = s.upper()
su
<class 'str'>
Out[30]:
'HELLO WORLD'
In [29]:
s[-1]
Out[29]:
'd'
In [33]:
a = "samrendra "
b = "kumar"
c = a + b
c
Out[33]:
'samrendra kumar'
In [34]:
name = input ("Enter Name : ")
Enter Name : Samrendra Kumar
In [36]:
print (name)
Samrendra Kumar
In [37]:
#lists (Grouping items together)
days_of_the_week = ['Sunday', 'Monday', 'Tuesday', 'Wednesday', 'Thursday', 'Friday', 'Saturday']
In [39]:
print (days_of_the_week[-1])
print (days_of_the_week[2])
print (days_of_the_week[-4])
Saturday
Tuesday
Wednesday
In [43]:
days_of_the_week.reverse()
days_of_the_week
Out[43]:
['Saturday', 'Friday', 'Thursday', 'Wednesday', 'Tuesday', 'Monday', 'Sunday']
In [48]:
languages = ['Fortran', 'C', 'C++']
languages.append('Python')
print (languages)
['Fortran', 'C', 'C++', 'Python']
In [49]:
languages.extend('Perl')
languages
Out[49]:
['Fortran', 'C', 'C++', 'Python', 'P', 'e', 'r', 'l']
In [50]:
list(range(10))
Out[50]:
[0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
In [53]:
evens = list(range(0,21,2))
evens
Out[53]:
[0, 2, 4, 6, 8, 10, 12, 14, 16, 18, 20]
In [56]:
#list unpacking
x,y = [1, 2]
x
Out[56]:
1
In [54]:
help(range)
Help on class range in module builtins:

class range(object)
 |  range(stop) -> range object
 |  range(start, stop[, step]) -> range object
 |  
 |  Return an object that produces a sequence of integers from start (inclusive)
 |  to stop (exclusive) by step.  range(i, j) produces i, i+1, i+2, ..., j-1.
 |  start defaults to 0, and stop is omitted!  range(4) produces 0, 1, 2, 3.
 |  These are exactly the valid indices for a list of 4 elements.
 |  When step is given, it specifies the increment (or decrement).
 |  
 |  Methods defined here:
 |  
 |  __bool__(self, /)
 |      self != 0
 |  
 |  __contains__(self, key, /)
 |      Return key in self.
 |  
 |  __eq__(self, value, /)
 |      Return self==value.
 |  
 |  __ge__(self, value, /)
 |      Return self>=value.
 |  
 |  __getattribute__(self, name, /)
 |      Return getattr(self, name).
 |  
 |  __getitem__(self, key, /)
 |      Return self[key].
 |  
 |  __gt__(self, value, /)
 |      Return self>value.
 |  
 |  __hash__(self, /)
 |      Return hash(self).
 |  
 |  __iter__(self, /)
 |      Implement iter(self).
 |  
 |  __le__(self, value, /)
 |      Return self<=value.
 |  
 |  __len__(self, /)
 |      Return len(self).
 |  
 |  __lt__(self, value, /)
 |      Return self<value.
 |  
 |  __ne__(self, value, /)
 |      Return self!=value.
 |  
 |  __new__(*args, **kwargs) from builtins.type
 |      Create and return a new object.  See help(type) for accurate signature.
 |  
 |  __reduce__(...)
 |      helper for pickle
 |  
 |  __repr__(self, /)
 |      Return repr(self).
 |  
 |  __reversed__(...)
 |      Return a reverse iterator.
 |  
 |  count(...)
 |      rangeobject.count(value) -> integer -- return number of occurrences of value
 |  
 |  index(...)
 |      rangeobject.index(value, [start, [stop]]) -> integer -- return index of value.
 |      Raise ValueError if the value is not present.
 |  
 |  ----------------------------------------------------------------------
 |  Data descriptors defined here:
 |  
 |  start
 |  
 |  step
 |  
 |  stop

Tupple

In [59]:
my_list = [1, 2]
my_tuple = (1, 2)
my_list[1] = 3
print (my_list)
[1, 3]
In [60]:
my_tuple
my_tuple[2]=3
print (my_tuple)
---------------------------------------------------------------------------
TypeError                                 Traceback (most recent call last)
<ipython-input-60-49c4e2bc87be> in <module>()
      1 my_tuple
----> 2 my_tuple[2]=3
      3 print (my_tuple)

TypeError: 'tuple' object does not support item assignment
In [61]:
x, y = 1, 2
x, y = y, x
x,y
Out[61]:
(2, 1)
Dictionary data type¶
In [62]:
empty_dict = {}
empty_dict2 = dict()
In [66]:
grades = {'Joel': 80, 'Tim' : 95}
print (grades)
joel_grade = grades['Joel']
print(joel_grade)
{'Joel': 80, 'Tim': 95}
80
In [74]:
# Control Statement
x=int(input('Please enter an Integer : '))

if x<0:
    X=0
    print("negative changed to Zero")
elif x ==0:
    print ('zero')
elif x==1:
    print('Single')
else:
    print('More')
Please enter an Integer : 9
More
In [79]:
x=int(input('Please enter an Integer : '))
if x%2==0:
    print(x, ' is even Number')
else:
    print(x, ' is odd Number')
Please enter an Integer : 3
3  is odd Number
In [83]:
a=[1,2,3]
[x**3 for x in a]
Out[83]:
[1, 8, 27]
In [84]:
a=range(10)
[x**2 for x in a]
Out[84]:
[0, 1, 4, 9, 16, 25, 36, 49, 64, 81]
In [90]:
days_of_the_week = ['Sunday','Monday','Tuesday','Wednesday','Thursday','Friday','Saturday']
for day in days_of_the_week:
    print('Today is ', day)
Today is  Sunday
Today is  Monday
Today is  Tuesday
Today is  Wednesday
Today is  Thursday
Today is  Friday
Today is  Saturday
In [91]:
count=0
while(count<5):
    print("Current count: ", count)
    count = count + 1
Current count:  0
Current count:  1
Current count:  2
Current count:  3
Current count:  4
In [92]:
i=0
while(i<10):
    a=i**2
    print("Square of ", i, 'is', a)
    i=i+1
Square of  0 is 0
Square of  1 is 1
Square of  2 is 4
Square of  3 is 9
Square of  4 is 16
Square of  5 is 25
Square of  6 is 36
Square of  7 is 49
Square of  8 is 64
Square of  9 is 81
Functions

In [94]:
def sum(x,y):
    s=x+y
    return s
sum(10,15)
Out[94]:
25
In [97]:
def my_func(x,y):
    s=x+y
    m=x*y
    return s,m
my_func(10,15)
Out[97]:
(25, 150)
In [103]:
a=int(input('Please enter an Integer : '))
def fact(n):
    if n<=0:
        return 1
    else:
        return n*fact(n-1)
fact(a)
Please enter an Integer : 5
Out[103]:
120
In [105]:
#function under function
a=int(input('Please enter an Integer : '))
def fact(n):
    if n<=0:
        return 1
    return n*fact(n-1)
fact(a)
Please enter an Integer : 4
Out[105]:
24
In [109]:
def my_func(x,y):
     return (x+y),(x*y)
my_func(10,15)
Out[109]:
(25, 150)
In [108]:
def f(x): return x**2
print (f(8))

g = lambda x: x**2
print(g(8))
64
64
In [110]:
print(g(5))
25

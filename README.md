# hello-world xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Just repository xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
This branch is created in September 12. xxxxxxxxxxxxxxxxxxxxxx


# -*- coding: utf-8 -*-
import sys
def foo(bar=None):
    if bar is None:
        bar = []
    bar.append("baz")
    try:
        l = ['a','1']
        print 'Begin'
        #int(l[0])
        int(l[1])
        print 'Go'
    #except IndexError,e:
    except (IndexError,ValueError) as e:
        print e
    #else:
    #print "No Error"
    finally:
        print 'Done'
    return bar
print foo()

odd = lambda x : bool(x%2)
numbers = [n for n in range(1,10)]
numbers[:] = [n for n in numbers if not odd(n)]
print numbers


'''
lst = [1,2,3]
def foo1():
    try:
        lst += [5]
    except BaseException as e:
        print e

print foo1()

'''



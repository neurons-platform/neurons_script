# neurons-platform script

Used to write simple scripts, For neurons-platform



# Grammar 

## variabal
```
a = 1
b = `hello`
c = `world
```

## if
```
if a eq 1
then
   print b + ` ` + c
fi
```

## while
```
a = 10
while a > 0 
do
  print a
  a = a - 1
  _lua("sleep","1")
done

```

## call lua function
```
// you can call lua function 
r = _lua("hello", "hello", "world")
print r
```

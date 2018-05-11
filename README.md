# "My 4 Favorite Ruby Methods"

### `.downcase`
makes every letter in a string lowercase
```
  "DANIEL".downcase #=> daniel
```

### `.rand`
generates a random number between a given range
```
  .rand(10) #=> 5
```

### `.all?`
will pass true if all items in the block are true
```
all_odd = [1,3].all? do |number| number.odd?
end #=> true
```

### `.select`
will return a new array of items that are true
```
[1,2,3,4,5].select do |number| number.even?
end #=> [2,4]
```

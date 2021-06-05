# arr_to_obj


### convert array to object by passing two arguments (array itself, key by which object has to be created, value)
### key works only when array is a list of objects

## examples

### 1
`input : [1,2,3,4,5], key can be anything but the output doesn't depend on this because array is not a list of object, null
output: {1:1,2:2,3:3,4:4,5:5}`

### 2
`input: [{name:"sai",loop:8},{name:"teja",loop:5},{name:"npm",loop:10}], name, null
output: {sai:{name:"sai",loop:8},teja:{name:"teja",loop:5},npm:{name:"npm",loop:10}}`

### 3
`input: [{name:"sai",loop:8},{name:"teja",loop:5},{name:"npm",loop:10}], name, loop
output: {sai:8,teja:5,npm:10}`

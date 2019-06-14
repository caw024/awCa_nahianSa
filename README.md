# Graphics Final Project: Team La CaSa
Calvin Aw and Sajed Nahian

Period 5

### Some Features
+ Mesh: can retrieve information 
```
mesh :filename.obj
```
+ Shading: done based on specified type

For Flat shading: at end of add_shape at mdl script, add flat
```
add_shape arg0 arg1 ... flat
```

For Gouraud shading: at end of add_shape at mdl_script, add gouraud
```
add_shape arg0 arg1 ... gouraud
```

Otherwise, if color isn't specified, it is assumed to be flat shading

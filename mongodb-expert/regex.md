### regex
#### Mencari string incasesensitive
```
[ 'name'=> [ 
    '$regex'   => '^'.$request->name.'$', 
    '$options' => '$i'
   ]
]
```

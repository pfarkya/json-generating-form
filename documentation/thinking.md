# uses
Like from the very begining of these project we need some proper documentation so that it gives value to user

# prerequiste 
# Before Uses Understand how it should start

# Actions
Decision How the JSONSchema should 
What tools I need to use to develop this library.
Who all are the audience for this librabry: <developer><UI><from creater><any one that needs form>

# Form Elements

1) Dependent (visibleIf=<condition>,classIf=<{className:condition}>,disabledIf=<condition>, requiredIf:<condition> manyMore Type Condition)
2) Non- dependent (name:""(can have variable to resolve/dynamically handled),placeholder:""(can have variable to resolve/dynamically handled),label:""(can have variable to resolve/dynamically handled),className:""(can have variable to resolve/dynamically handled))
3) dynamically dependent (multiProperty dependent(needs contructor) or singleProperty Dependent)
4) crudable
5) theme that can be change anywhere MultiLevel Theming Multiple Theming

Get 3 themes(on 3 different screen size) and use it


# Proper Examples



# Demo Page

"JSON Schema to set to create form"
```
{
"type":""
"<property-name>": <property-detailed-json>(if type is object)
}
```

"property-detailed-json"
```
{
"name":"<exact as property-name>",
"placeholder":""
"validator":"<function,pattern>"
"validation-message": {"required":,"pattern","anyCustomRule":},
"ValidationMessageOnChangeShow":
"dependentOn":<expression>,
"class":<doc>,
"style":<doc>,
"classIf":<doc>,

}
```


element-type: crudable object(rearrangable), crudable array(rearrangable), object, multiselect, select, input, textarea, checkbox, toggle, tags(return array of string),
input-type: number,email,text,checkbox,radio
required:
select-option:<list arrayofstring or arrayofobject{display:"",value:""}>
multiselect will return alway array
select always return value(can be any thing)

suggestions

Searchable
searchfrom


How to handle expression {root.fullname.name} {root.array[i(denote current index if element is child or sibs else it will be syntatical error)]}

array[i] same context array[x] other context

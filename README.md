# dataTables.treeGrid.js
TreeGrid extension for jquery DataTables@1.10.19

## Demo
[https://homfen.github.io/dataTables.treeGrid.js](https://homfen.github.io/dataTables.treeGrid.js)

## Options
```left```: indent of children

```expandIcon```: expand icon html

```collapseIcon```: collapse icon html

## Usage
the row data should contain a property "children" as blow:
```
{
"data": 
    [
        {
            "name": "Tiger Nixon",
            ...
            "children": [
                {
                    "name": "Hermione Butler",
                    ...
                }
            ]
        }
    ]
}            
```
the js initialization part as blow:
```html
$('#example').DataTable({
    'treeGrid': {
        'left': 10,
        'expandIcon': '<span>+</span>',
        'collapseIcon': '<span>-</span>'
    }
});
```

## License
MIT license.

# dataTables.treeGrid.js
TreeGrid extension for jquery DataTables

## Demo
[https://homfen.github.io/dataTables.treeGrid.js](https://homfen.github.io/dataTables.treeGrid.js)

## settings
```left```: indent of children

```expandIcon```: expand icon html

```collapseIcon```: collapse icon html

## usage
```
$('#example').DataTable({
    'treeGrid': {
        'left': 10,
        'expandIcon': '+<\/span>',
        'collapseIcon': '-<\/span>'
    }
});
```

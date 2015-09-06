# Dropdown menu manager

This plugin adds the feature to describe with the help of the CKEditor's configuration various dropdowns
and populate them with desirable items.

## Configuration example

```javascript
 config.dropdownmenumanager={
        'Widgets': {
          items: [{
            label: 'Widgets',
            command: 'theCommandExecutedOnClick',
            order: 1
            }],
          label: {
            text: 'Widgets',
            width: 45
          }
        },
 };
```

To add the dropdowns on the toolbar use the keys in the 'config.dropdownmenumanager' object , in this case:
'Widgets'

Simple toolbar:

```javascript
 config.toolbar = [
    ['Widgets']
  ];
```

In order to show the dropdown menu's label you should not use the default CKEditor iframe functionallity.
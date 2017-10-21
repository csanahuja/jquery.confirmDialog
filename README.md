# jquery.confirmDialog
Jquery confirmDialog without Boostrap

## Example
![Example](https://i.gyazo.com/55265fec5a154308982fa30f0c2f4b02.png)

## Usage

```
 $('#trigger').click(function(){
	$.createDialog({
		attachAfter: '#content',
		title: 'Are you sure you want to continue?',
		accept: 'Yes',
		refuse: 'Cancel',
		acceptStyle: 'red',
		refuseStyle: 'gray',
		acceptAction: function(){
			//Do danger thing
		}
	});
	$.showDialog();
});
```

> **#trigger** will be the element that will show the warning dialog when clicked


## Params

> **attachAfter** element after which the dialog html structure will be placed.

> **title** string to be shown as dialog title.

> **accept** string to the "accept" button.

> **refuse** string to the "refuse" button.

> **acceptStyle** style to the "accept" button. It's the name of a css class. You can add more styles in the confirmDialog.css.

> **refuseStyle** style to the "refuse" button. It's the name of a css class. You can add more styles in the confirmDialog.css.

> **acceptAction** function (without params) that will be executed by clicking the "accept" button.

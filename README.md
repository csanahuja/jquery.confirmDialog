# jquery.confirmDialog
Jquery confirmDialog without Boostrap

## Example
![Example]https://i.gyazo.com/55265fec5a154308982fa30f0c2f4b02.png

## Usage

>		$('#trigger').click(function(){
			$.createDialog({
				attachAfter: '#content',
				title: 'Are you sure you want to continue?',
				accept: 'Yes',
				refuse: 'Cancel',
				acceptStyle: 'red',
				refuseStyle: 'gray',
				acceptAction: processDangerAction
			});
			$.showDialog();
		});
		
>		function processDangerAction(){
		  //DangerAction
		}
 

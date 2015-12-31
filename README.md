# jquery.confirmDialog
Jquery confirmDialog without Boostrap

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

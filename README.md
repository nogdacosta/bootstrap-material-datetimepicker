# bootstrap-material-datetimepicker
DateTimePicker for bootstrap-material

### Updates

| Date				| Author			| Description											 |
| ----------------- | ----------------- | ------------------------------------------------------ |
| 2015-06-18		| T00rk 			| Fixed Timepicker rendering bug						 |
| 2015-06-16		| T00rk 			| Use Timepicker alone / Display short time (12 hours)	 |
| 2015-06-13		| T00rk 			| Fixed issue with HTML value tag 						 |
| 2015-05-25		| T00rk 			| Changed repo name to bootstrap-material-datetimepicker * |
| 2015-05-12		| T00rk				| Added parameters for button text						 |
| 2015-05-05		| Sovanna			| FIX undefined _minDate in isBeforeMaxDate func		 |
| 2015-04-10		| T00rk				| Little change in clock design							 |
| 2015-04-10		| Peterzen			| Added bower and requirejs support						 |
| 2015-04-08		| T00rk				| Fixed problem on locale switch						 |
| 2015-03-04		| T00rk				| Added Time picker										 |
(\*) File names have been changed 

bootstrap-material-datepicker.js => bootstrap-material-date**time**picker.js

bootstrap-material-datepicker.css => bootstrap-material-date**time**picker.css
	
### Prerequisites

Bootstrap 3 [http://getbootstrap.com/](http://getbootstrap.com/)

bootstrap-material-design [http://fezvrasta.github.io/bootstrap-material-design/](http://fezvrasta.github.io/bootstrap-material-design/)

jquery [http://jquery.com/download/](http://jquery.com/download/)

momentjs [http://momentjs.com/](http://momentjs.com/)

### Live Example

Click [here](http://t00rk.github.io/bootstrap-material-datetimepicker/) to see

### Usage

	$('input').bootstrapMaterialDatePicker();

### bower

	bower install bootstrap-material-datetimepicker
	
### Parameters

| Name				| Type							| Description									|
| ----------------- | ----------------------------- | --------------------------------------------- |
| **format**		| String						| MomentJS Format								|
| **shortTime**		| Boolean						| true => Display 12 hours AM|PM 				|
| **minDate**		| (String\|Date\|Moment)		| Minimum selectable date						|
| **maxDate**		| (String\|Date\|Moment)		| Maximum selectable date						|
| **currentDate**	| (String\|Date\|Moment)		| Initial Date									|
| **date**			| Boolean						| true => Has Datepicker						|
| **time**			| Boolean						| true => Has Timepicker						|
| **cancelText**	| String						| Text for the cancel button (default: Cancel)	|
| **okText**		| String						| Text for the OK button (default: OK)			|


### Events

| Name				| Parameters				| Description										|
| ----------------- | ------------------------- | ------------------------------------------------- |
| **beforeChange**	| event, date				| OK button is clicked								|
| **change**		| event, date				| OK button is clicked and input value is changed	|
| **dateSelected**	| event, date				| New date is selected								|


### Methods

        $('input').bootstrapMaterialDatePicker('setDate', moment());

| Name				| Parameter					| Description					|
| ----------------- | ------------------------- | ----------------------------- |
| **setDate**		| (String\|Date\|Moment)	| Set initial date				|
| **setMinDate**	| (String\|Date\|Moment)	| Set minimum selectable date	|
| **setMaxDate**	| (String\|Date\|Moment)	| Set maximum selectable date	|
| **destroy**		| NULL						| Destroy the datepicker		|

	

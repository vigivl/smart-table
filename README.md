# smart-table v0.1 (alfa)
Filter, sort and paginate HTML tables with a simple jQuery plugin.
See index.html for examples.
Notice: Your table should contain thead and tbody tags.

### Available options:
* filterOn: true or false (default true) - enable or disable filter row;
* sortingOn: true of false (default true) - enable or disable sort asc/desc buttons;
* hideColumnOn: true or false (default true) - enable or disable hide column button;
* sortAscHtml: 'html' (default '<span></span>') - HTML for sort ascending button;
* sortDescHtml: 'html' (default '<span></span>') - HTML for sort descending button;
* hideColumnHtml: 'html' (default 'x') - HTML for hide column button;
* zebraClass: null or 'css-class' (default 'zebra-odd-bg') - if not null then will be added to every odd tr;
* paginationPerPage: number (default 10) - enable pagination if greater than zero.

### Usage:
```html
<head>
<script src="https://code.jquery.com/jquery-2.1.4.min.js"></script>
<script src="smart-table.js"></script>
<link rel="stylesheet" href="smart-table.css">
</head>
```
```javascript
$(function() {
	$('.st-table').smartTable({
	  filterOn: false,
	  paginationPerPage: 5
	});
});
```

Simple Fields WordPress Custom Fields Plugin
============================================

Simple Fields is a WordPress plugin that adds visual Custom Fields, 
hence making them more usably for end users (aka customers). 

This version here at GitHub is the development version. Please see
http://wordpress.org/extend/plugins/simple-fields/
for the latest and stable version.

* See http://simple-fields.com for getting started guides and API documentation.
* Author: [Pär Thernström](https://twitter.com/eskapism "@eskapism")

## Screenshots

Works great for attachments

![Screenshot 2](http://simple-fields.com/wordpress/wp-content/uploads/2012/09/feature-image-repeatable-fields11.png)

Mix fields any way you want to

![Screenshot 1](http://simple-fields.com/wordpress/wp-content/uploads/2012/09/feature-fields-types.png)

## Field Types

There are many built in custom field types in Simple Fields:

* Color picker field
* Date- & Timepicker field
* Dropdown field
* File field
* Checkbox field
* Radiobutton field
* Textarea/HTML/TinyMCE field
* and more ...

## Usage
```php
<?php

$textfield_output = simple_fields_value("my_text_field");
$file_attachment = simple_fields_value("my_file_field");

?>
```

# lravel-die-and-dump-in-raw-php-project
Use Laravel's dd() and dump() function in your raw php project.
View well formatted output of php's Variable, Array, Object etc.

## Installation
  Just incude or require this file 'vendor/autoload.php' and call dd() or dump().

### Examplecode
  
```php
<?php
	require 'vendor/autoload.php';// include or require this file so that you can use dd(), dump()

	class Example{
		public $country = "Bangladesh";
		public $city = "Dhaka";
		private $mobile = "+88123456";
	}

	$object = new Example;
	dump($object);// Calling dump()

	$array = [
		'name'=>'abc',
		'phone'=>'+12345',
		'address'=>[
			'city'=>'Dhaka',
			'country'=>'Bangladesh'
		]
	];
	dd($array);// Calling dd()
?>
```
### Output

![Image of Yaktocat](https://raw.githubusercontent.com/anisurrahmansagor/lravel-die-and-dump-in-raw-project/master/Output.jpg)


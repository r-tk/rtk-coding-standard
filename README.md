# RTK Coding Standard

[![Latest version](https://img.shields.io/packagist/v/r-tk/rtk-coding-standard.svg)](https://packagist.org/packages/r-tk/rtk-coding-standard)
[![License](https://img.shields.io/packagist/l/r-tk/rtk-coding-standard.svg)](https://packagist.org/packages/r-tk/rtk-coding-standard)
[![Total Downloads](https://img.shields.io/packagist/dt/r-tk/rtk-coding-standard.svg)](https://packagist.org/packages/r-tk/rtk-coding-standard)

add to composer
```
	"require-dev": {
		"r-tk/rtk-coding-standard": "*"
	}
```

link `phpcs.xml`
```xml
<?xml version="1.0" encoding="UTF-8"?>
<ruleset name="RTK Coding Standard">

	<rule ref="./vendor/r-tk/rtk-coding-standard/phpcs.xml"/>

	<file>./src</file>
	<file>./tests</file>

</ruleset>
```
# kohana 3.3 pagination

# 安装

```
composer require "caojiabin/pagination
```


# 使用admin模板，在config.php下添加pagination.php

```
<?php
defined('SYSPATH') or die('No direct script access.');

return array(

	// Application defaults
	'default' => array(
		'current_page'      => array('source' => 'query_string', 'key' => 'page'), // source: "query_string" or "route"
		'total_items'       => 0,
		'items_per_page'    => 20,
		'view'              => 'pagination/admin',
		'auto_hide'         => TRUE,
		'first_page_in_url' => FALSE,
	),

);
```

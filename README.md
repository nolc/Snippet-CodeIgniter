Snippet-CodeIgniter
===================

Sublime Text 2 Snippets para codeigniter

##Install
To install: clone to SublimeCodeigniter within your Sublime Text 2 package folder.


#Shortcuts 

**Controller**

`cic + tab`   


```php
<?php if ( ! defined('BASEPATH')) exit('No direct script access allowed');

class Name extends CI_Controller
{ 
	public function __construct()
	{
		parent::__construct();
	}

	public function index()
	{
		
        
	}

}
/* End of file README.md */
/* Location: ./application/controllers/README.md */

```

**Model**


`cim + tab`  

```php
<?php (defined('BASEPATH')) OR exit('No direct script access allowed');

class Name_Model extends CI_Model
{
	public function __construct()
	{
		parent::__construct();
	}

}
/* End of file welcome.php */
/* Location: ./application/models/README.md */

```


**Library**

`tll + tab`

```php
$this->load->library('');
```


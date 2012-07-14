Snippet-CodeIgniter
===================

Sublime Text 2 Snippets para codeigniter

Install
To install: clone to SublimeCodeigniter within your Sublime Text 2 package folder.


#Shortcuts 

`cic + tab`   


**Genera la clase Controller**

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


`cim + tab`    Genera la clase Modelo

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
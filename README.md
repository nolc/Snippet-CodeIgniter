Snippet-CodeIgniter
===================

Sublime Text 2 Snippets codeigniter

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

**Load Model**

`tlm + tab`

```php
<?php
$this->load->model('');
```

**Load View**

`tlv + tab`

```php
<?php
$this->load->view('');
```


**Load Library**

`tll + tab`

```php
<?php
$this->load->library('');
```

**Load Helper**

`tlh + tab`

```php
<?php
$this->load->helper('');
```

**input post**

`tip + tab`

```php
<?php
$this->input->post('');
```

**uri segment**

`tus + tab`

```php
<?php
$this->uri->segment();
```
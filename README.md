Pagination Config for Codeigniter
================

This is the config file of codeigniter, had set the style match the Twitter's Bootstrap. have fun and use it.


# Usage
```
/* 
| Put the main file into application > config.
| 1. You can autoload it, or
| 2. You can load this config in your controllers.
*/

// 1. Autoload
// In application/config/autoload.php around line 82

$autoload['config'] = array('pagination');

// 2. Manually

$this->load->config('pagination');

```

---------

# Notice

After you had load the config file, you still need to setup the `base url` and `total_rows` of the pagination array.

```
// Config Pagination
$pagination               = $this->config->config['pagination'];
$pagination['base_url']   = 'the/base/url/you/want/to/use';
$pagination['total_rows'] = 1000;

```

---------

# License

Don't worry about this, feel free to use.

----------

# Links
Checkout the docs if you still don't know how to use.

* [Codeigniter - Pagination](http://ellislab.com/codeigniter/user-guide/libraries/pagination.html)
* [Codeigniter - Using Config](http://ellislab.com/codeigniter/user-guide/libraries/config.html)

Thanks for the love of [Bootstrap](http://twitter.github.io/bootstrap/)

-----

*2013 &copy; Vincent Chen*
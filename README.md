## Description:
This an AJAX multi-level comment system, that allows infinite level comment and replies.

## How to Install:
You can install the comment system very easily by using composer. You just have to run:

`composer require magkopian/php-infinite-multi-level-comments`

Alternatively you can add it as a dependency in you `composer.json` file,

```JSON
{
	"require": {
		"magkopian/php-infinite-multi-level-comments": "1.0.*"
	}
}
```

and run `composer install`.

After installing the comment system move the `Config.template.php` file to `src/classes/Config.php` and
add your database credentials to it.

After that, use the `sql/inf_comments.sql` to generate the `comment` table in your database.

Finally, copy the `public_html` directory inside the directory you have installed the comment system
(the directory that contains the `vendor` folder).

You can try the comment system by running the demo.php from your browser.
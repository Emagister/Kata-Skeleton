# HERE YOU HAVE TO PUT ALL YOUR TESTS #

## STANDARD TEST SKELETON ##

Put this as your test skeleton, after install composer packages and configure your namespaces at the
```bootstrap.php``` file

```
<?php

namespace My\Namespaces;

use \PHPunit_Framework_TestCase;

class MyTest extends PHPUnit_Framework_TestCase
{
    public function setUp
    {
        // Set up your fixture
    }

    public function tearDown()
    {
        // Tear down your fixture
    }

    // Your test cases
}
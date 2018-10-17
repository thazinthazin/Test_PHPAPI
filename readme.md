## Ref - https://www.codeofaninja.com/2017/02/create-simple-rest-api-in-php.html

## API - URL

[PRODUCT]
http://localhost/api/product/read.php

http://localhost/api/product/create.php
in Request Body(raw)
{
    "name" : "Amazing Pillow 2.0",
    "price" : "199",
    "description" : "The best pillow for amazing programmers.",
    "category_id" : 2,
    "created" : "2018-06-01 00:35:07"
}

http://localhost/api/product/read_one.php?id=60

http://localhost/api/product/update.php
in Request Body(raw)
{
    "id" : "61",
    "name" : "Amazing Pillow 3.0",
    "price" : "255",
    "description" : "The best pillow for amazing programmers.",
    "category_id" : 2,
    "created" : "2018-08-01 00:35:07"
}

http://localhost/api/product/delete.php
in Request Body(raw)
{
    "id" : "61"
}

http://localhost/api/product/search.php?s=shirt

http://localhost/api/product/read_paging.php

[CATEGORY]
http://localhost/api/category/read.php
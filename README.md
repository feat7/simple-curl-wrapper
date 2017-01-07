# simple-curl-wrapper
Simple class to access curl easily.

# Use
<?php
include 'Curl.php';

//For get Requests

$return = Curl::get('http://example.com');

//For post Requests

$postData = ['data1' = 'value1', 'data2' = 'value2']; //post data array

$return = Curl::post('http://example.com', $postData);

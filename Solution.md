# Bee-Box-Solutions
Getting started with BeeBox, BWAPP. Written Solutions with explaination

What is Cross Site Scripting (XSS)?
Cross-Site Scripting (XSS) attacks are a type of injection, in which malicious scripts are injected into otherwise benign and trusted websites. XSS attacks occur when an attacker uses a web application to send malicious code, generally in the form of a browser side script, to a end user.


Types of XSS Attacks :

1)Stored XSS - Type I (Persistent) 
          Stored attacks are those where the injected script is permanently stored on the target servers, such as in a database, in a message forum, visitor log, comment field, etc. The victim then retrieves the malicious script from the server when it requests the stored information

2)Reflected XSS - Type II (Non-Persistent) 
          Reflected attacks are those where the injected script is reflected off the web server, such as in an error message, search result, or any other response that includes some or all of the input sent to the server as part of the request. Reflected attacks are delivered to victims via another route, such as in an e-mail message, or on some other website.

3)DOM Based XSS - Type-0 
         DOM Based XSS is a attack wherein the attack payload is executed as a result of modifying the DOM “environment” in the victim’s browser used by the original client side script, so that the client side code runs in an “unexpected” manner.That is, the page itself (the HTTP response that is) does not change, but the client side code contained in the page executes differently due to the malicious modifications that have occurred in the DOM environment. 

For more Refer : https://www.owasp.org/index.php/Cross-site_Scripting_(XSS)
                 https://www.owasp.org/index.php/DOM_Based_XSS  

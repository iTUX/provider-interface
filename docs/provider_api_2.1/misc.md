# Övergripande Information

## Endpoints

Bas-urlen till APIt: http://ituxportalen.se/pubapi.php/2.1/
För att testa att api är uppe: http://ituxportalen.se/pubapi.php/ping

Bas-urlen till stage-APIt: http://stage.ituxportalen.se/pubapi.php/2.1/
För att testa att api är uppe: http://stage.ituxportalen.se/pubapi.php/ping

Under bas-urlen förväntas tjänsterna finnas, bland annat /orders/ (http://ituxportalen.se/pubapi.php/2.1/orders/) och /accesses/ (http://ituxportalen.se/pubapi.php/2.1/accesses/)

## Autentisering

Autentisering av Service Provider sker genom HTTP BASIC. Se [RFC-2617][rfc2617]. 

[rfc2617]: http://www.ietf.org/rfc/rfc2617.txt "HTTP Authentication: Basic and Digest Access Authentication"

## Character Encoding

Alla APIer använder UTF-8. 


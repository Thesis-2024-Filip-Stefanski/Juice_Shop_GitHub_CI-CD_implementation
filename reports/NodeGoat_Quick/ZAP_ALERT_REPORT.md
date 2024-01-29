# Juice Shop scann report


## Summary of Alerts

| Risk Level | Number of Alerts |
| --- | --- |
| High | 0 |
| Medium | 4 |
| Low | 4 |
| Informational | 0 |




## Alerts

| Name | Risk Level | Number of Instances |
| --- | --- | --- |
| Content Security Policy (CSP) Header Not Set | Medium | 46 |
| Cross-Domain Misconfiguration | Medium | 41 |
| Missing Anti-clickjacking Header | Medium | 39 |
| Session ID in URL Rewrite | Medium | 156 |
| Cross-Domain JavaScript Source File Inclusion | Low | 18 |
| Private IP Disclosure | Low | 1 |
| Timestamp Disclosure - Unix | Low | 5 |
| X-Content-Type-Options Header Missing | Low | 156 |




## Alert Detail



### [ Content Security Policy (CSP) Header Not Set ](https://www.zaproxy.org/docs/alerts/10038/)



##### Medium (High)

### Description

Content Security Policy (CSP) is an added layer of security that helps to detect and mitigate certain types of attacks, including Cross Site Scripting (XSS) and data injection attacks. These attacks are used for everything from data theft to site defacement or distribution of malware. CSP provides a set of standard HTTP headers that allow website owners to declare approved sources of content that browsers should be allowed to load on that page — covered types are JavaScript, CSS, HTML frames, fonts, images and embeddable objects such as Java applets, ActiveX, audio and video files.

* URL: http://npm:3000/
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/assets/public/favicon_js.ico
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/main.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/polyfills.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/runtime.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/styles.css
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/.git/vendor.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHLd&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2k&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAQ&sid=25bXLdRCcIYJnsayAAAE
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPe&sid=XObG3WIR01nOTZlNAAAG
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILdS&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_V&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMe&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCO&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINxv&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKm&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOtw&sid=7nJlPUHurreffFJYAAAU
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo-&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV2&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVU&sid=mdYZyLMJditeTU1xAAAa
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRH5&sid=8s91GlJRcInIItVOAAAc
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxB&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS5S&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6E&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITD_&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP0&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPf&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYK&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7F&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUft&sid=9WW0YI_tB215JVOVAAAw
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUUd&sid=CljmHVnnTiObKjZCAAAt
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxk&sid=agRfiTJThQSzwSYNAAAx
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHd&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVoS&sid=r3zKO-90lanwGqkxAAA3
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1p&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW7S&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRi&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0G&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJ8&sid=0ytWpBW35-zpJab8AAA_
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXuh&sid=--T-1T_sZTjf1UZSAABB
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXur&sid=tKcovsbmZV-t34-vAABC
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxC&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZI&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTs&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvf&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `POST`
  * Parameter: ``
  * Attack: ``
  * Evidence: ``
  * Other Info: ``

Instances: 46

### Solution

Ensure that your web server, application server, load balancer, etc. is configured to set the Content-Security-Policy header.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/Security/CSP/Introducing_Content_Security_Policy ](https://developer.mozilla.org/en-US/docs/Web/Security/CSP/Introducing_Content_Security_Policy)
* [ https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html ](https://cheatsheetseries.owasp.org/cheatsheets/Content_Security_Policy_Cheat_Sheet.html)
* [ http://www.w3.org/TR/CSP/ ](http://www.w3.org/TR/CSP/)
* [ http://w3c.github.io/webappsec/specs/content-security-policy/csp-specification.dev.html ](http://w3c.github.io/webappsec/specs/content-security-policy/csp-specification.dev.html)
* [ http://www.html5rocks.com/en/tutorials/security/content-security-policy/ ](http://www.html5rocks.com/en/tutorials/security/content-security-policy/)
* [ http://caniuse.com/#feat=contentsecuritypolicy ](http://caniuse.com/#feat=contentsecuritypolicy)
* [ http://content-security-policy.com/ ](http://content-security-policy.com/)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3

### [ Cross-Domain Misconfiguration ](https://www.zaproxy.org/docs/alerts/10098/)



##### Medium (Medium)

### Description

Web browser data loading may be possible, due to a Cross Origin Resource Sharing (CORS) misconfiguration on the web server

* URL: http://NPM:3000
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/assets/public/favicon_js.ico
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://NPM:3000/.git/index
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/main.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/polyfills.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/runtime.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/styles.css
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/.git/vendor.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/api/Challenges/%3Fname=Score%2520Board
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/api/Quantitys/
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/i18n/en.json
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/favicon_js.ico
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/hackingInstructor.png
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/JuiceShop_Logo.png
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/apple_juice.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/apple_pressings.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/artwork2.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/banana_juice.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/carrot_juice.jpeg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/eggfruit_juice.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/fan_facemask.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/fruit_press.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/green_smoothie.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/lemon_juice.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/melon_bike.jpeg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/assets/public/images/products/permafrost.jpg
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/font-mfizz.woff
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/main.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/MaterialIcons-Regular.woff2
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/polyfills.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/admin/application-configuration
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/admin/application-version
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/captcha/
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/languages
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/products/search%3Fq=
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/rest/user/whoami
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/runtime.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/styles.css
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/tutorial.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`
* URL: http://npm:3000/vendor.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `Access-Control-Allow-Origin: *`
  * Other Info: `The CORS misconfiguration on the web server permits cross-domain read requests from arbitrary third party domains, using unauthenticated APIs on this domain. Web browser implementations do not permit arbitrary third parties to read the response from authenticated APIs, however. This reduces the risk somewhat. This misconfiguration could be used by an attacker to access data that is available in an unauthenticated manner, but which uses some other form of security, such as IP address white-listing.`

Instances: 41

### Solution

Ensure that sensitive data is not available in an unauthenticated manner (using IP address white-listing, for instance).
Configure the "Access-Control-Allow-Origin" HTTP header to a more restrictive set of domains, or remove all CORS headers entirely, to allow the web browser to enforce the Same Origin Policy (SOP) in a more restrictive manner.

### Reference


* [ https://vulncat.fortify.com/en/detail?id=desc.config.dotnet.html5_overly_permissive_cors_policy ](https://vulncat.fortify.com/en/detail?id=desc.config.dotnet.html5_overly_permissive_cors_policy)


#### CWE Id: [ 264 ](https://cwe.mitre.org/data/definitions/264.html)


#### WASC Id: 14

#### Source ID: 3

### [ Missing Anti-clickjacking Header ](https://www.zaproxy.org/docs/alerts/10020/)



##### Medium (Medium)

### Description

The response does not include either Content-Security-Policy with 'frame-ancestors' directive or X-Frame-Options to protect against 'ClickJacking' attacks.

* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHLd&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2k&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAQ&sid=25bXLdRCcIYJnsayAAAE
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPe&sid=XObG3WIR01nOTZlNAAAG
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILdS&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_V&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMe&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCO&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINxv&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKm&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOtw&sid=7nJlPUHurreffFJYAAAU
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo-&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV2&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVU&sid=mdYZyLMJditeTU1xAAAa
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRH5&sid=8s91GlJRcInIItVOAAAc
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxB&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS5S&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6E&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITD_&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP0&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPf&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYK&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7F&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUft&sid=9WW0YI_tB215JVOVAAAw
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUUd&sid=CljmHVnnTiObKjZCAAAt
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxk&sid=agRfiTJThQSzwSYNAAAx
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHd&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVoS&sid=r3zKO-90lanwGqkxAAA3
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1p&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW7S&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRi&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0G&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJ8&sid=0ytWpBW35-zpJab8AAA_
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXuh&sid=--T-1T_sZTjf1UZSAABB
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXur&sid=tKcovsbmZV-t34-vAABC
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxC&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZI&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTs&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvf&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `POST`
  * Parameter: `x-frame-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: ``

Instances: 39

### Solution

Modern Web browsers support the Content-Security-Policy and X-Frame-Options HTTP headers. Ensure one of them is set on all web pages returned by your site/app.
If you expect the page to be framed only by pages on your server (e.g. it's part of a FRAMESET) then you'll want to use SAMEORIGIN, otherwise if you never expect the page to be framed, you should use DENY. Alternatively consider implementing Content Security Policy's "frame-ancestors" directive.

### Reference


* [ https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options ](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/X-Frame-Options)


#### CWE Id: [ 1021 ](https://cwe.mitre.org/data/definitions/1021.html)


#### WASC Id: 15

#### Source ID: 3

### [ Session ID in URL Rewrite ](https://www.zaproxy.org/docs/alerts/3/)



##### Medium (High)

### Description

URL rewrite is used to track user session ID. The session ID may be disclosed via cross-site referer header. In addition, the session ID might be stored in browser history or server logs.

* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHM6&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `I7I4X5inxe7hoy0kAAAA`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHOB&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `I7I4X5inxe7hoy0kAAAA`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2l&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `nygHk0OIjKBqRkkZAAAC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII8r&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `nygHk0OIjKBqRkkZAAAC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAR&sid=25bXLdRCcIYJnsayAAAE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `25bXLdRCcIYJnsayAAAE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJI0&sid=25bXLdRCcIYJnsayAAAE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `25bXLdRCcIYJnsayAAAE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKfg&sid=XObG3WIR01nOTZlNAAAG
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `XObG3WIR01nOTZlNAAAG`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPy&sid=XObG3WIR01nOTZlNAAAG
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `XObG3WIR01nOTZlNAAAG`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILd-&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `YH9d9WrzS9k-OXRrAAAI`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILuP&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `YH9d9WrzS9k-OXRrAAAI`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_a&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mu1Ixd0uyrisu0F8AAAM`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMg&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `vZXYvnsUBmJ32RYeAAAK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMTt&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `vZXYvnsUBmJ32RYeAAAK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCP&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `6sSX-WBF5ipcfqX7AAAO`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINI-&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mu1Ixd0uyrisu0F8AAAM`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINUz&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `6sSX-WBF5ipcfqX7AAAO`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINy3&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `3P2-87dEtAAKTgl2AAAQ`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKo&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Pe367Ih1ehCdZNx9AAAS`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKW&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `3P2-87dEtAAKTgl2AAAQ`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOuI&sid=7nJlPUHurreffFJYAAAU
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `7nJlPUHurreffFJYAAAU`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOZf&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Pe367Ih1ehCdZNx9AAAS`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIP7E&sid=7nJlPUHurreffFJYAAAU
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `7nJlPUHurreffFJYAAAU`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo8&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8JqjaiacqQeI5cUeAAAW`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo_&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fg-tlkGMOOwtjk1hAAAX`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV4&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8JqjaiacqQeI5cUeAAAW`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQ4K&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fg-tlkGMOOwtjk1hAAAX`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVd&sid=mdYZyLMJditeTU1xAAAa
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mdYZyLMJditeTU1xAAAa`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQw7&sid=mdYZyLMJditeTU1xAAAa
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mdYZyLMJditeTU1xAAAa`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRHG&sid=8s91GlJRcInIItVOAAAc
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8s91GlJRcInIItVOAAAc`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRX3&sid=8s91GlJRcInIItVOAAAc
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8s91GlJRcInIItVOAAAc`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxC&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `FGxLCnu9JLD8JpzsAAAf`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS68&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `4-mz4tPoxUP3LbSlAAAe`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6G&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `sbJJdvnkJrFrQOlTAAAg`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6p&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `FGxLCnu9JLD8JpzsAAAf`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISHe&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `sbJJdvnkJrFrQOlTAAAg`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISWM&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `4-mz4tPoxUP3LbSlAAAe`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITdr&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `uP_A_SaOKjynTm7XAAAl`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITE0&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `NY6YjgJI6hw-3MfsAAAk`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITjb&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0yEvuOEGNLvOsBPAAAm`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITm7&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `NY6YjgJI6hw-3MfsAAAk`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP2&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0yEvuOEGNLvOsBPAAAm`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPo&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `uP_A_SaOKjynTm7XAAAl`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITu7&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0aBPlGNpmik_IR7AAAn`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYR&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0aBPlGNpmik_IR7AAAn`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7G&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z5u0U18ut_kS-RZuAAAs`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUdA&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z5u0U18ut_kS-RZuAAAs`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUfu&sid=9WW0YI_tB215JVOVAAAw
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9WW0YI_tB215JVOVAAAw`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUU-&sid=CljmHVnnTiObKjZCAAAt
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `CljmHVnnTiObKjZCAAAt`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxm&sid=agRfiTJThQSzwSYNAAAx
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `agRfiTJThQSzwSYNAAAx`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUya&sid=9WW0YI_tB215JVOVAAAw
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9WW0YI_tB215JVOVAAAw`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIV1c&sid=CljmHVnnTiObKjZCAAAt
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `CljmHVnnTiObKjZCAAAt`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVF-&sid=agRfiTJThQSzwSYNAAAx
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `agRfiTJThQSzwSYNAAAx`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHe&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fYVvJcfVVTQptyl0AAAv`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVp7&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `r3zKO-90lanwGqkxAAA3`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1s&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fWQZbIOx0LFByMaMAAA4`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW5g&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `r3zKO-90lanwGqkxAAA3`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW80&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `muZqxqsHZh7AkD4DAAA2`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW9J&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `r3zKO-90lanwGqkxAAA3`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWc9&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `muZqxqsHZh7AkD4DAAA2`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWnJ&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Y1mSt1McVNHb4R1dAAA7`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRn&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Y1mSt1McVNHb4R1dAAA7`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWUg&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fWQZbIOx0LFByMaMAAA4`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0g&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `ZREl2KWWqRr1bHBQAAA-`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXgr&sid=0ytWpBW35-zpJab8AAA_
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `0ytWpBW35-zpJab8AAA_`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJd&sid=0ytWpBW35-zpJab8AAA_
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `0ytWpBW35-zpJab8AAA_`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXKI&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `ZREl2KWWqRr1bHBQAAA-`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXrj&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9AZ6WF265Hpa5yn5AABD`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXui&sid=--T-1T_sZTjf1UZSAABB
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `--T-1T_sZTjf1UZSAABB`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXvL&sid=tKcovsbmZV-t34-vAABC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `tKcovsbmZV-t34-vAABC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxh&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z72ahMpmhXyvcbKyAABE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZL&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9AZ6WF265Hpa5yn5AABD`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYI-&sid=--T-1T_sZTjf1UZSAABB
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `--T-1T_sZTjf1UZSAABB`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYnX&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `OuWLRRWsU9C5X_WtAABK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTd&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z72ahMpmhXyvcbKyAABE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYUC&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `OuWLRRWsU9C5X_WtAABK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvh&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `MM3uJjCGiXH9L7xTAABL`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYWD&sid=tKcovsbmZV-t34-vAABC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `tKcovsbmZV-t34-vAABC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIZ7Q&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `MM3uJjCGiXH9L7xTAABL`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=--T-1T_sZTjf1UZSAABB
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `--T-1T_sZTjf1UZSAABB`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=0ytWpBW35-zpJab8AAA_
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `0ytWpBW35-zpJab8AAA_`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=25bXLdRCcIYJnsayAAAE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `25bXLdRCcIYJnsayAAAE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `3P2-87dEtAAKTgl2AAAQ`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `4-mz4tPoxUP3LbSlAAAe`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `6sSX-WBF5ipcfqX7AAAO`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=7nJlPUHurreffFJYAAAU
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `7nJlPUHurreffFJYAAAU`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8JqjaiacqQeI5cUeAAAW`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=8s91GlJRcInIItVOAAAc
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8s91GlJRcInIItVOAAAc`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9AZ6WF265Hpa5yn5AABD`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=9WW0YI_tB215JVOVAAAw
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9WW0YI_tB215JVOVAAAw`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=agRfiTJThQSzwSYNAAAx
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `agRfiTJThQSzwSYNAAAx`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0aBPlGNpmik_IR7AAAn`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0yEvuOEGNLvOsBPAAAm`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=CljmHVnnTiObKjZCAAAt
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `CljmHVnnTiObKjZCAAAt`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fg-tlkGMOOwtjk1hAAAX`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `FGxLCnu9JLD8JpzsAAAf`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fWQZbIOx0LFByMaMAAA4`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fYVvJcfVVTQptyl0AAAv`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `I7I4X5inxe7hoy0kAAAA`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=mdYZyLMJditeTU1xAAAa
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mdYZyLMJditeTU1xAAAa`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `MM3uJjCGiXH9L7xTAABL`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mu1Ixd0uyrisu0F8AAAM`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `muZqxqsHZh7AkD4DAAA2`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `NY6YjgJI6hw-3MfsAAAk`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `nygHk0OIjKBqRkkZAAAC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `OuWLRRWsU9C5X_WtAABK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Pe367Ih1ehCdZNx9AAAS`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `r3zKO-90lanwGqkxAAA3`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `sbJJdvnkJrFrQOlTAAAg`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=tKcovsbmZV-t34-vAABC
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `tKcovsbmZV-t34-vAABC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `uP_A_SaOKjynTm7XAAAl`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `vZXYvnsUBmJ32RYeAAAK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=XObG3WIR01nOTZlNAAAG
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `XObG3WIR01nOTZlNAAAG`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Y1mSt1McVNHb4R1dAAA7`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `YH9d9WrzS9k-OXRrAAAI`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z5u0U18ut_kS-RZuAAAs`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z72ahMpmhXyvcbKyAABE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=websocket&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `GET`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `ZREl2KWWqRr1bHBQAAA-`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHLd&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `I7I4X5inxe7hoy0kAAAA`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2k&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `nygHk0OIjKBqRkkZAAAC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAQ&sid=25bXLdRCcIYJnsayAAAE
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `25bXLdRCcIYJnsayAAAE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPe&sid=XObG3WIR01nOTZlNAAAG
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `XObG3WIR01nOTZlNAAAG`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILdS&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `YH9d9WrzS9k-OXRrAAAI`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_V&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mu1Ixd0uyrisu0F8AAAM`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMe&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `vZXYvnsUBmJ32RYeAAAK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCO&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `6sSX-WBF5ipcfqX7AAAO`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINxv&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `3P2-87dEtAAKTgl2AAAQ`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKm&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Pe367Ih1ehCdZNx9AAAS`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOtw&sid=7nJlPUHurreffFJYAAAU
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `7nJlPUHurreffFJYAAAU`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo-&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fg-tlkGMOOwtjk1hAAAX`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV2&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8JqjaiacqQeI5cUeAAAW`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVU&sid=mdYZyLMJditeTU1xAAAa
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `mdYZyLMJditeTU1xAAAa`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRH5&sid=8s91GlJRcInIItVOAAAc
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `8s91GlJRcInIItVOAAAc`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxB&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `FGxLCnu9JLD8JpzsAAAf`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS5S&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `4-mz4tPoxUP3LbSlAAAe`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6E&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `sbJJdvnkJrFrQOlTAAAg`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITD_&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `NY6YjgJI6hw-3MfsAAAk`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP0&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0yEvuOEGNLvOsBPAAAm`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPf&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `uP_A_SaOKjynTm7XAAAl`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYK&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `B0aBPlGNpmik_IR7AAAn`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7F&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z5u0U18ut_kS-RZuAAAs`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUft&sid=9WW0YI_tB215JVOVAAAw
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9WW0YI_tB215JVOVAAAw`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUUd&sid=CljmHVnnTiObKjZCAAAt
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `CljmHVnnTiObKjZCAAAt`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxk&sid=agRfiTJThQSzwSYNAAAx
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `agRfiTJThQSzwSYNAAAx`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHd&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fYVvJcfVVTQptyl0AAAv`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVoS&sid=r3zKO-90lanwGqkxAAA3
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `r3zKO-90lanwGqkxAAA3`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1p&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `fWQZbIOx0LFByMaMAAA4`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW7S&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `muZqxqsHZh7AkD4DAAA2`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRi&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Y1mSt1McVNHb4R1dAAA7`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0G&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `ZREl2KWWqRr1bHBQAAA-`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJ8&sid=0ytWpBW35-zpJab8AAA_
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `0ytWpBW35-zpJab8AAA_`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXuh&sid=--T-1T_sZTjf1UZSAABB
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `--T-1T_sZTjf1UZSAABB`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXur&sid=tKcovsbmZV-t34-vAABC
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `tKcovsbmZV-t34-vAABC`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxC&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `Z72ahMpmhXyvcbKyAABE`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZI&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `9AZ6WF265Hpa5yn5AABD`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTs&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `OuWLRRWsU9C5X_WtAABK`
  * Other Info: ``
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvf&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `POST`
  * Parameter: `sid`
  * Attack: ``
  * Evidence: `MM3uJjCGiXH9L7xTAABL`
  * Other Info: ``

Instances: 156

### Solution

For secure content, put session ID in a cookie. To be even more secure consider using a combination of cookie and URL rewrite.

### Reference


* [ http://seclists.org/lists/webappsec/2002/Oct-Dec/0111.html ](http://seclists.org/lists/webappsec/2002/Oct-Dec/0111.html)


#### CWE Id: [ 200 ](https://cwe.mitre.org/data/definitions/200.html)


#### WASC Id: 13

#### Source ID: 3

### [ Cross-Domain JavaScript Source File Inclusion ](https://www.zaproxy.org/docs/alerts/10017/)



##### Low (Medium)

### Description

The page includes one or more script files from a third-party domain.

* URL: http://NPM:3000
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://NPM:3000
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/assets/public/favicon_js.ico
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/assets/public/favicon_js.ico
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://NPM:3000/.git/index
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://NPM:3000/.git/index
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/main.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/main.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/polyfills.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/polyfills.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/runtime.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/runtime.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/styles.css
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/styles.css
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/vendor.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/cookieconsent2/3.1.0/cookieconsent.min.js"></script>`
  * Other Info: ``
* URL: http://npm:3000/.git/vendor.js
  * Method: `GET`
  * Parameter: `//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js`
  * Attack: ``
  * Evidence: `<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>`
  * Other Info: ``

Instances: 18

### Solution

Ensure JavaScript source files are loaded from only trusted sources, and the sources can't be controlled by end users of the application.

### Reference



#### CWE Id: [ 829 ](https://cwe.mitre.org/data/definitions/829.html)


#### WASC Id: 15

#### Source ID: 3

### [ Private IP Disclosure ](https://www.zaproxy.org/docs/alerts/2/)



##### Low (Medium)

### Description

A private IP (such as 10.x.x.x, 172.x.x.x, 192.168.x.x) or an Amazon EC2 private hostname (for example, ip-10-0-56-78) has been found in the HTTP response body. This information might be helpful for further attacks targeting internal systems.

* URL: http://npm:3000/rest/admin/application-configuration
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `192.168.99.100:3000`
  * Other Info: `192.168.99.100:3000
192.168.99.100:4200
`

Instances: 1

### Solution

Remove the private IP address from the HTTP response body.  For comments, use JSP/ASP/PHP comment instead of HTML/JavaScript comment which can be seen by client browsers.

### Reference


* [ https://tools.ietf.org/html/rfc1918 ](https://tools.ietf.org/html/rfc1918)


#### CWE Id: [ 200 ](https://cwe.mitre.org/data/definitions/200.html)


#### WASC Id: 13

#### Source ID: 3

### [ Timestamp Disclosure - Unix ](https://www.zaproxy.org/docs/alerts/10096/)



##### Low (Low)

### Description

A timestamp was disclosed by the application/web server - Unix

* URL: http://npm:3000/main.js
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1734944650`
  * Other Info: `1734944650, which evaluates to: 2024-12-23 09:04:10`
* URL: http://npm:3000/rest/admin/application-configuration
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1969196030`
  * Other Info: `1969196030, which evaluates to: 2032-05-26 14:53:50`
* URL: http://npm:3000/rest/admin/application-configuration
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1970691216`
  * Other Info: `1970691216, which evaluates to: 2032-06-12 22:13:36`
* URL: http://npm:3000/rest/products/search%3Fq=
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1969196030`
  * Other Info: `1969196030, which evaluates to: 2032-05-26 14:53:50`
* URL: http://npm:3000/rest/products/search%3Fq=
  * Method: `GET`
  * Parameter: ``
  * Attack: ``
  * Evidence: `1970691216`
  * Other Info: `1970691216, which evaluates to: 2032-06-12 22:13:36`

Instances: 5

### Solution

Manually confirm that the timestamp data is not sensitive, and that the data cannot be aggregated to disclose exploitable patterns.

### Reference


* [ http://projects.webappsec.org/w/page/13246936/Information%20Leakage ](http://projects.webappsec.org/w/page/13246936/Information%20Leakage)


#### CWE Id: [ 200 ](https://cwe.mitre.org/data/definitions/200.html)


#### WASC Id: 13

#### Source ID: 3

### [ X-Content-Type-Options Header Missing ](https://www.zaproxy.org/docs/alerts/10021/)



##### Low (Medium)

### Description

The Anti-MIME-Sniffing header X-Content-Type-Options was not set to 'nosniff'. This allows older versions of Internet Explorer and Chrome to perform MIME-sniffing on the response body, potentially causing the response body to be interpreted and displayed as a content type other than the declared content type. Current (early 2014) and legacy versions of Firefox will use the declared content type (if one is set), rather than performing MIME-sniffing.

* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHDa
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHM6&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHOB&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHv1
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2l&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII8r&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII_7
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAR&sid=25bXLdRCcIYJnsayAAAE
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJI0&sid=25bXLdRCcIYJnsayAAAE
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKDU
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKfg&sid=XObG3WIR01nOTZlNAAAG
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPy&sid=XObG3WIR01nOTZlNAAAG
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIL_X
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILd-&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILUM
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILuP&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_a&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMg&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMqT
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMTt&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIN0f
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCP&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINI-&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINUz&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINy3&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINYs
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIO1g
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOb6
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKo&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKW&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOuI&sid=7nJlPUHurreffFJYAAAU
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOZf&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIP7E&sid=7nJlPUHurreffFJYAAAU
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIP84
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo8&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo_&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPQL
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV4&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQ4K&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQEY
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVd&sid=mdYZyLMJditeTU1xAAAa
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQw7&sid=mdYZyLMJditeTU1xAAAa
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQzt
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRHG&sid=8s91GlJRcInIItVOAAAc
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRmY
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRpT
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRqD
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRX3&sid=8s91GlJRcInIItVOAAAc
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxC&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS-o
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS68&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6G&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6p&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISHe&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISrZ
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISua
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLISWM&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIT-T
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITAu
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITdr&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITE0&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITjb&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITkq
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITm7&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP2&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPo&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITu7&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYR&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7G&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUdA&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUfu&sid=9WW0YI_tB215JVOVAAAw
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUHo
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUT4
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUTy
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUU-&sid=CljmHVnnTiObKjZCAAAt
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxm&sid=agRfiTJThQSzwSYNAAAx
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUya&sid=9WW0YI_tB215JVOVAAAw
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIV1c&sid=CljmHVnnTiObKjZCAAAt
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVF-&sid=agRfiTJThQSzwSYNAAAx
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHe&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVmX
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVp7&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVPE
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVSD
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1s&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW5g&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW6Q
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW80&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW9J&sid=r3zKO-90lanwGqkxAAA3
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWc9&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWfQ
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWnJ&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRn&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWUg&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWva
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0g&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX8z
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXC-
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXC1
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXEK
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXgr&sid=0ytWpBW35-zpJab8AAA_
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJd&sid=0ytWpBW35-zpJab8AAA_
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXKI&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXrj&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXui&sid=--T-1T_sZTjf1UZSAABB
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXvL&sid=tKcovsbmZV-t34-vAABC
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxh&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXy7
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZL&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYI-&sid=--T-1T_sZTjf1UZSAABB
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYnX&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYRp
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTd&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYUC&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvh&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYWD&sid=tKcovsbmZV-t34-vAABC
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIZ7Q&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `GET`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIHLd&sid=I7I4X5inxe7hoy0kAAAA
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLII2k&sid=nygHk0OIjKBqRkkZAAAC
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIJAQ&sid=25bXLdRCcIYJnsayAAAE
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIKPe&sid=XObG3WIR01nOTZlNAAAG
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLILdS&sid=YH9d9WrzS9k-OXRrAAAI
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIM_V&sid=mu1Ixd0uyrisu0F8AAAM
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIMMe&sid=vZXYvnsUBmJ32RYeAAAK
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINCO&sid=6sSX-WBF5ipcfqX7AAAO
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLINxv&sid=3P2-87dEtAAKTgl2AAAQ
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOKm&sid=Pe367Ih1ehCdZNx9AAAS
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIOtw&sid=7nJlPUHurreffFJYAAAU
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPo-&sid=fg-tlkGMOOwtjk1hAAAX
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIPV2&sid=8JqjaiacqQeI5cUeAAAW
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIQVU&sid=mdYZyLMJditeTU1xAAAa
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRH5&sid=8s91GlJRcInIItVOAAAc
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIRxB&sid=FGxLCnu9JLD8JpzsAAAf
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS5S&sid=4-mz4tPoxUP3LbSlAAAe
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIS6E&sid=sbJJdvnkJrFrQOlTAAAg
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITD_&sid=NY6YjgJI6hw-3MfsAAAk
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITP0&sid=B0yEvuOEGNLvOsBPAAAm
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITPf&sid=uP_A_SaOKjynTm7XAAAl
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLITYK&sid=B0aBPlGNpmik_IR7AAAn
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIU7F&sid=Z5u0U18ut_kS-RZuAAAs
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUft&sid=9WW0YI_tB215JVOVAAAw
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUUd&sid=CljmHVnnTiObKjZCAAAt
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIUxk&sid=agRfiTJThQSzwSYNAAAx
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVHd&sid=fYVvJcfVVTQptyl0AAAv
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIVoS&sid=r3zKO-90lanwGqkxAAA3
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW1p&sid=fWQZbIOx0LFByMaMAAA4
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIW7S&sid=muZqxqsHZh7AkD4DAAA2
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIWRi&sid=Y1mSt1McVNHb4R1dAAA7
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIX0G&sid=ZREl2KWWqRr1bHBQAAA-
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXJ8&sid=0ytWpBW35-zpJab8AAA_
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXuh&sid=--T-1T_sZTjf1UZSAABB
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXur&sid=tKcovsbmZV-t34-vAABC
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXxC&sid=Z72ahMpmhXyvcbKyAABE
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIXZI&sid=9AZ6WF265Hpa5yn5AABD
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYTs&sid=OuWLRRWsU9C5X_WtAABK
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`
* URL: http://npm:3000/socket.io/%3FEIO=4&transport=polling&t=OrLIYvf&sid=MM3uJjCGiXH9L7xTAABL
  * Method: `POST`
  * Parameter: `x-content-type-options`
  * Attack: ``
  * Evidence: ``
  * Other Info: `This issue still applies to error type pages (401, 403, 500, etc.) as those pages are often still affected by injection issues, in which case there is still concern for browsers sniffing pages away from their actual content type.
At "High" threshold this scan rule will not alert on client or server error responses.`

Instances: 156

### Solution

Ensure that the application/web server sets the Content-Type header appropriately, and that it sets the X-Content-Type-Options header to 'nosniff' for all web pages.
If possible, ensure that the end user uses a standards-compliant and modern web browser that does not perform MIME-sniffing at all, or that can be directed by the web application/web server to not perform MIME-sniffing.

### Reference


* [ http://msdn.microsoft.com/en-us/library/ie/gg622941%28v=vs.85%29.aspx ](http://msdn.microsoft.com/en-us/library/ie/gg622941%28v=vs.85%29.aspx)
* [ https://owasp.org/www-community/Security_Headers ](https://owasp.org/www-community/Security_Headers)


#### CWE Id: [ 693 ](https://cwe.mitre.org/data/definitions/693.html)


#### WASC Id: 15

#### Source ID: 3



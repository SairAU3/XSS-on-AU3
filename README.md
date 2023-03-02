# XSS-on-AU3
The scanner on AU3 allows you to identify web application vulnerabilities, such as such as information disclosure, XSS injection, command execution, and software identification software. In addition to the basic scanning shown earlier, AU3 allows the penetration tester to customize the scanning of a specific target.

## Content
* XSS-Finder
* Features
* Dump and Write Information
* DOM Scanner for Syncs
* Payloads
* False positives
* Installation in Windows

## XSS-Finder
![xss](https://user-images.githubusercontent.com/126814634/222519937-b23fd59a-4353-47ad-b90a-eafdc1019b18.jpg)

### Features
* Blind XSS
* Saved XSS using a file
* Persistent XSS using a file
* Reflected XSS
* Reflected XSS URLs in paths
* DOM XSS
* Special Java XSS payloads
* Cached pages XSS
* Forms-based XSS
* HTTP Link XSS
* HTTP Host XSS
* HTTP Referer XSS
* HTTP Cookies XSS
* HTTP Location XSS
* Server Value Dump

## Dumping and recording information
* Dumper can create server parameters, forms, etc.
* Dumper will write the response to the results file
* Use grep to check for reflections

## DOM scanner for syncs
Example:
` <script> var x = document.URL.substring(document.URL.indexOf("name=")+5);document.write(name + "!"); </script> `

## Payloads
* Use payloads, update payloads, add more payloads

## False positives.
* Be sure to remove all new rows, tabs, etc. to reduce false positives in reports

![xss2](https://user-images.githubusercontent.com/126814634/222521273-9170938f-87e5-4d2c-82b9-206fc3e73581.jpg)

## Installation in Windows
Download and install from the official website
(https://www.autoitscript.com/site/autoit/downloads/)
Right click on the file "XSS.au3" and click Run Script



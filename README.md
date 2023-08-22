
# SOAP & REST api - NumberToWords

Welcome to the NumberToWords API Integration project! This GitHub repository hosts a comprehensive solution for integrating the SOAP and REST APIs provided by the NumberConversion.wso web service. The primary goal of this project is to automate the conversion of numerical values into their corresponding words, allowing you to leverage this functionality in your applications and systems.




### Features:


SOAP and REST API integration

Automated testing suite

Clear documentation

Open for contributions


### Get Started :
Clone the repo, follow the docs, and enhance number-to-words conversion in your applications. Let's make numbers speak!
## POST SOAP - NumberToWords

##### URL
https://www.dataaccess.com/webservicesserver/NumberConversion.wso

```
```

##### Request Headers
```
Content-Type:text/xml; charset=utf-8

Content-Length:length

```
```
```
##### Body raw (xml)

```
<?xml version="1.0" encoding="utf-8"?>
<soap12:Envelope xmlns:soap12="http://www.w3.org/2003/05/soap-envelope">
  <soap12:Body>
    <NumberToWords xmlns="http://www.dataaccess.com/webservicesserver/">
      <ubiNum>444</ubiNum>
    </NumberToWords>
  </soap12:Body>
</soap12:Envelope>

```

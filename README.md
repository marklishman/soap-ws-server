
# WSDL

    http://localhost:8080/ws/countries.wsdl
    
# Postman

URL: `http://localhost:8080/ws`<br>
Method: `POST`<br>
Content Type: `text/xml`<br>
Body

    <soapenv:Envelope xmlns:soapenv="http://schemas.xmlsoap.org/soap/envelope/"
    				  xmlns:gs="http://spring.io/guides/gs-producing-web-service">
       <soapenv:Header/>
       <soapenv:Body>
          <gs:getCountryRequest>
             <gs:name>Spain</gs:name>
          </gs:getCountryRequest>
       </soapenv:Body>
    </soapenv:Envelope>


# Reference

    https://spring.io/guides/gs/producing-web-service/
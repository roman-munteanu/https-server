https-server
-----

Generate keystore.p12
```
"C:\Program Files\Java\jdk1.8.0_231\bin\keytool.exe" -genkeypair -alias tomcat -keyalg RSA -keysize 2048 -storetype PKCS12 -keystore keystore.p12 -validity 3650

password
```

list the details:
```
"C:\Program Files\Java\jdk1.8.0_231\bin\keytool.exe" -list -v -storetype pkcs12 -keystore keystore.p12
```


Endpoint:
https://localhost:8443/status
200
```
OK
```

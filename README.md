# curlmail

Curlmail è un semplice container docker che eseguito su una macchia remota permettere a chiunche di inviare email usanto una chiamata CURL

```
docker run -d \
  -e GMAIL_USERNAME=samsepiol@gmail.com \
  -e GMAIL_PASSWORD=R0B0TT0N \  
  -p 80:80 javanile/curlmail
```

```
curl -s http://localhost -H "Token:1234"  -d "subject=Hello" -d "body=World!"
```


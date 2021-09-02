# curlmail


```
docker run -d -p 80:80 \
  -e GMAIL_USERNAME=samsepiol@gmail.com \
  -e GMAIL_PASSWORD=R0B0TT0N \
  javanile/curlmail
```

```
curl -s http://localhost -d "subject=Hello" -d "body=World!"
```


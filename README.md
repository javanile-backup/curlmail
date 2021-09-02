# curlmail


```
docker run -d \
  -e GMAIL_USERNAME=samsepiol@gmail.com \
  -e GMAIL_PASSWORD=R0B0TT0N \
  -p 80:80 javanile/curlmail
```

```
curl -s http://localhost -d "subject=Hello" -d "body=World!"
```


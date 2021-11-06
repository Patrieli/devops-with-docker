##### Commands

- docker run -d --rm -it --name ubuntu ubuntu sh -c 'echo "Input website:"; read website; echo "Searching.."; sleep 1; curl http://$website;'
- docker exec -it ubuntu /bin/sh
- apt-get -qq update
- apt-get -qq -y install curl

*Exited container*

- docker attach ubuntu
- helsinki.fi

**Output**:

```
Searching..
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="https://www.helsinki.fi/">here</a>.</p>
</body></html>```
```


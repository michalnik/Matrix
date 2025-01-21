# Matrix Animation
## Background
I don't need any special licence here to show this animation inspired by film [Matrix][1].
But you know, it is like characters - I mean letters, numbers or others - whose are colored green and are falling
down similar as it is [here][2].

## How to run it
It is most simple as it can be - open the `index.html` in the browser (*I did not hesitate to test it elsewhere than [Chrome][3]*).
I think it could work in most favourites or known browsers in the world daily used for browsing the net.

Or if you prefer to be more *romantic*, run [python][4] simple www server ...

```bash
# presume python3 is in your system installed
python -m http.server
# stdout prints:
# Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...

# You can change the address and port to be more specific with
python -m http.server -b localhost 8080
# stdout prints:
# Serving HTTP on 127.0.0.1 port 8080 (http://127.0.0.1:8080/) ...

# You can be like ROOT of your system and provide standard web page at localhost with sudo (linux)
sudo python -m http.server -b localhost 80
# stdout prints
# Serving HTTP on 127.0.0.1 port 80 (http://127.0.0.1:80/) ...
```

Then open your browser and fill desired URL in the search/URL input line, for example `localhost` for the last option for serving
web pages with python.

## Reason for the project appeared here
Even though I am not big fan of FE things as I was in the past, this was a challenge for me to create it and show somehow my FE
capabilities. Because the problem is quite simple, I won't explain the details, please study the code.

[1]: <https://www.imdb.com/title/tt0133093/> "The Matrix"
[2]: <https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExZmZ6ZTJnNWI5bHVrMmVpb3JraHpkNWNpbGFtcHB4YTUxbmFjdDN4ZiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/AOSwwqVjNZlDO/giphy.gif> "Matrix from Giphy"
[3]: <https://www.google.com/chrome/> "Chrome homepage"
[4]: <https://www.python.org/> "Python homepage"

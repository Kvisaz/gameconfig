# HTML5 Game Config
Common Game Config Description


## URL parameters
All games can change its behavior through url parameters:

```
http://site.com/game.html?param1=val1&param2=val2
```

### Dictionary / d / dict
Array of string pairs for word learning games. 

- param name: dict
- param name shortcut: d
- param value: word00#word01##word10#word11
- encoding: word delimiter # , pair delimiter ##

```
http://site.com/game.html?d=word00#word01##word10#word11
```

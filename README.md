# turkcealtyazi.org.script
Film ve diziler için www.turkcealtyazi.org Python3 scripti

# Kurulum:
Beautifulsoap, parse-torrent-name ve rarfile modülleri kurulu olmalıdır:

```pip3 install bs4```

```pip3 install lxml```

```pip3 install rarfile```

```pip3 install parse-torrent-name```

Windows içinde çalıştırıyorsanız pip3 install parse-torrent-name hata verecektir. O halde şu komutla parse-torrent-name kurabilirsiniz:

```pip3 install https://github.com/divijbindlish/parse-torrent-name/archive/master.zip```

# Kullanım:

```python3 altyazi.py "/Volumes/movies"```

veya (Windows'da \ yerine / kullanın)

```python3 altyazi.py "C:/Users/Aa Bb/Movies"```
# wget-fotolog
Save your fotolog profile before they close, with a simple command:

```
wget -H -r -l1 -k -p \
 -D "www.fotolog.com,fotolog.com,$(echo sp{{1..10},{a..e}}.fotolog.com | tr ' ' ,)" \
  http://www.fotolog.com/youruser/mosaic/
```

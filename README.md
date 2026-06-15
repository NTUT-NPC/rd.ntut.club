# rd.ntut.club

修改 `_redirects` 檔案

格式參考 https://developers.cloudflare.com/pages/configuration/redirects/

範例：
```
/home301 / 301
/home302 / 302
/querystrings /?query=string 301
/twitch https://twitch.tv
/trailing /trailing/ 301
/notrailing/ /nottrailing 301
/page/ /page2/#fragment 301
/blog/* https://blog.my.domain/:splat
/products/:code/:name /products?code=:code&name=:name
```

限制：
- 2000 條靜態規則
- 100 條動態規則

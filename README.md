# my-basket

個人が管理する Scoop バケットである。

## 導入

```powershell
scoop bucket add my https://github.com/rtmnkt/my-basket
scoop install my/app-name
```

`my` は利用側のバケット名であり、別の識別名に置き換えられる。アプリの追加は `bucket/<アプリ名>.json` を置く。

まだ `checkver` や `autoupdate` は未対応。

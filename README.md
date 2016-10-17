### Fetch PUT-PATCH(-DELETE-POST) Demo

Update to [javan/fetch-put-patch-demo](https://github.com/javan/fetch-put-patch-demo) showing
that Edge's `fetch()` implementation still breaks on `DELETE` request bodies.

- Original [github/fetch bug for PUT/PATCH](https://github.com/github/fetch/issues/340)
- Original [Edge bug for PUT/PATCH](https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/7773267/)
- [First mention of broken DELETE](https://github.com/github/fetch/issues/170#issuecomment-253884135)
- [Associated Edge Bug](https://developer.microsoft.com/en-us/microsoft-edge/platform/issues/9383422/)

##### Screenshot

![](/screenshot.png)


#### To Run

```bash
bundle install
rackup
```

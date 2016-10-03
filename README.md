# FrontierNav Internationalisation

Repository for internationalising [FrontierNav](https://frontiernav.jahed.io/) data.


## Contributions

Feel free to contribute via Pull Requests.

Make sure language files are in the form:

```
nodes.{[ISO 639-1 Language Code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes)}.json
```

The files themselves are just mapping Node IDs to text. You can see what the ID corresponds to by checking the base `en`
file and also checking the ID in the app itself by going to `https://frontiernav.jahed.io/nodes/{Node ID}`.

If you don't want to translate something and let it fallback to English, just don't include it in the file.

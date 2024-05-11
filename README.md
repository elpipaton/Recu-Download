Use `.\recu-windows-amd64.exe "--help"` for more information

Run with `.\recu-windows-amd64.exe`

First run will generate `config.json`, fill in urls to download and Cookie and User-Agent with header info using the network DevTools in Chrome
```Json
{
	"urls": [
		""
	],
	"header": {
		"Cookie": "",
		"User-Agent": ""
	},
}
```

Usage: `recurbate <json location> playlist/series <playlist.m3u8>`

`<json location>` is the location of the json

specifying `playlist` will cause the program to download only the .m3u8 file

specifying `series` will cause the program to download the videos serially instead of in parallel

specifying `playlist <playlist.m3u8>` will read the playlist from the location specified from `<playlist.m3u8>` and download that video

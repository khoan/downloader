download playlist.m3u8

# Usage

- locate playlist in browser
- copy CURL request
- `date; ./down 'https://streaming.host/playlist.m3u8' -H 'User-Agent: Mozilla/5.0 (Macintosh; Intel Mac OS X 10_13_1) AppleWebKit/604.3.5 (KHTML, like Gecko) Version/11.0.1 Safari/604.3.5' -H 'Accept: */*' -H 'Connection: keep-alive' -H 'Accept-Encoding: gzip' -H 'Accept-Language: en-au' -H 'X-Playback-Session-Id: abc' output.mp4`

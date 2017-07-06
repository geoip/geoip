# GEO IP 2 (Wordpress Edition)

Geo IP 2 is a cloud based ip geo identifier, currently only works for requests from Wordpress.

  - Handles up to 33-200k requests a second max
  - IP Database updated weekly
  - Completely free (fair usage aplies)

# How it works

GEO IP 2 can only currently be used from wordpress websites, we recommend integrating it with a wordpress plugin as shown in the files attached.

The api endpoint is shown below

```sh
http://geoip2.io/api/update/?&url=http://github.com/&agent=UserAgent&ip=85.255.235.215&p=9&v=0&siteurl=http://wpdomain.com&geo=true
```

### Plugins

GEO IP 2 is currently known to be used on the following plugins:

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md] [PlDb] |
| Github | [plugins/github/README.md] [PlGh] |
| Google Drive | [plugins/googledrive/README.md] [PlGd] |
| OneDrive | [plugins/onedrive/README.md] [PlOd] |
| Medium | [plugins/medium/README.md] [PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md] [PlGa] |


### Development

Want to contribute? Great!

Simply contact us at kevin.danna@wpdevs.co.uk


**Free Software, Hell Yeah!**

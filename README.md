# fix-orientation-environment

fix orientation for 360 panorama photo

## How to use

start xvfb:

```console
$ Xvfb :1 -screen 0 1024x768x24 &
```

add `DISPLAY` environment variable (if nothing):

```console
$ export DISPLAY=:1
```

fix orientation:

```console
$ ./ricoh-theta/convert.sh *.jpg
```

## Dependencies

- [mbirth/ricoh-theta](https://github.com/mbirth/ricoh-theta)

## License

The MIT license.

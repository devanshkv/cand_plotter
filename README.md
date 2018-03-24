# FRB candidate viewer

This code can be used for plotting FRB candidates. This is the fredda verison.
The given example reads fof'ed version, but the cfg file can be modified to use the fredda.cand file.

### Prerequisites

pandas
bokeh 0.12.6
[sigpyproc] (https://github.com/ewanbarr/sigpyproc)
stsci.convolve
~~mbplotlib~~

### Deploying

Simply deploy on your system and create a ~/.candplotter.cfg file based on the included example and run a bokeh server.
```
bokeh serve main.py
```

## Contributing

Any contributions welcome.

## Authors

* **Stefan Oslowski** - *Initial work* - [homepage](https://astronomy.swin.edu.au/~soslowski)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* get_fbank_data is based on Wael's filplot


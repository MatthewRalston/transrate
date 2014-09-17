<p align="center">
  <img alt="Transrate - understand your transcriptome assembly" src="https://github.com/Blahah/transrate/raw/master/docs/transrate_logo_full.png">
</p>

## Development status
[travis]: https://travis-ci.org/MatthewRalston/transrate

This version of transrate is no longer being developed.

## Installation
This requires ruby, ruby[gem]s, 1 gem: bundle


```
gem install bundler
```

This fork:


```
git clone https://github.com/MatthewRalston/transrate.git
cd transrate
bundle install
bundle exec rake compile
bundle exec bin/transrate --install-deps
bundle exec rake
```

Simply add the executable at ```bin/transrate``` to your PATH



## Citation
This fork of transrate is being maintained by Matthew Ralston.


Transrate is pre-publication academic software. If you use it, please cite the github repository and the DOI: [![DOI](https://zenodo.org/badge/3687/Blahah/transrate.png)](http://dx.doi.org/10.5281/zenodo.11039).

## Documentation

**transrate** is documented [on the website](http://hibberdlab.com/transrate).

The additional options are documented in the ```--help``` option

## Contributing

Interested in helping? Great! We particularly would like help with the following:

- code review
- documentation review
- adding features
- tackling bugs

For any of these, please just pick an appropriate issue [on the tracker](https://github.com/Blahah/transrate/issues) and make a pull request.

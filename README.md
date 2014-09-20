<p align="center">
  <img alt="Transrate - understand your transcriptome assembly" src="https://github.com/Blahah/transrate/raw/master/docs/transrate_logo_full.png">
</p>

## Development status
[travis]: https://travis-ci.org/MatthewRalston/transrate

This version of transrate is no longer being developed and is called Transrate-0.3.1

## Installation
This requires ruby, ruby[gem]s
I suggest using an [rvm](http://rvm.io) gemset to house the bundled gems.




This fork:


```
[rvm gemset create transrate && rvm gemset use transrate]{Optional}
git clone https://github.com/MatthewRalston/transrate.git
cd transrate
gem build transrate.gemspec
gem install transrate-0.3.1m.gem
transrate --install-deps
```

If the executable is not locatable ```which transrate```, add the EXECUTABLE DIRECTORY from the output of ```gem environment``` to your ```PATH```.



## Citation
This fork of transrate is being maintained by Matthew Ralston.


Transrate is pre-publication academic software. If you use it, please cite the github repository and the DOI: [![DOI](https://zenodo.org/badge/3687/Blahah/transrate.png)](http://dx.doi.org/10.5281/zenodo.11039).

## Documentation

**transrate** is documented [on the website](http://hibberdlab.com/transrate).
The additional options are documented in the ```--help``` option

#### New Features:
- transcript alignment to reference genome + stats
- strand-specific and unpaired read support
- recovery of singleton reads

## Contributing

Interested in helping? Great! We particularly would like help with the following:

- code review
- documentation review
- adding features
- tackling bugs

For any of these, please just pick an appropriate issue [on the tracker](https://github.com/Blahah/transrate/issues) and make a pull request.

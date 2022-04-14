# Aemulator
Implements the skeleton of the Aemulus emulator API. Each individual emulator must subclass this superclass and implement certain, standard methods. 
This is achieved by the use of `python` Abstract Base Classes, `ABCMeta`. See [this documentation](https://docs.python.org/2/library/abc.html#abc.abstractmethod) for details.
It can appear scary at times, but the gist is this: it is *impossible* to implement a subclass of Aemulator without implementing
 each method decorated with `@abstractmethod`. It is **strongly** reccomended that all emulators in the 
Aemulus Project subclass Aemulator, to ensure a consistent API across all implenetations by different authors. 


Install by calling:

`git clone https://github.com/AemulusProject/Aemulator.git`
`cd Aemulator`
`python setup.py install --user`

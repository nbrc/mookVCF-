# mookVCF~
A digital approximation of the iconic Moog VCF implemented in a Max external object.  
Original code from moc.erehwon@tsaot and [musicdsp.org](http://musicdsp.org) community.  
From Stilson & Smith [paper](https://ccrma.stanford.edu/~stilti/papers/moogvcf.pdf) (CCRMA). 

## How to install the external
- Drag and drop `/mookVCF` folder into your Max8 Packages folder.

### Requirements
Max7 or Max8 must be installed on your computer.

## How to build a new one
- Drag and drop the build folder content into a new folder `/mookVCF~`.  
- Drag and drop the newly created folder into your `/max-sdk-8.2/source/audio/` folder.
- Launch Terminal
- `cd [your path to the SDK]/max-sdk-8.2/source/audio/mookVCF~`
- `cmake -G Xcode`

### Requirements
CMake and Xcode must be installed on your computer. 

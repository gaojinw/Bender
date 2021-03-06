# Change Log
All notable changes to Bender will be documented in this file.

## [0.5.0](https://github.com/xmartlabs/Bender/releases/tag/0.5.0)

Added:

* BatchNorm
* Support for multiple inputs
* Add support for depthwise and atrous (dilated) convolutions in iOS 11
* Change some kernels to run on half instead of float
* Use MPSTemporaryImage by default

and some fixes.

## [0.4.1](https://github.com/xmartlabs/Bender/releases/tag/0.4.1)

* Support for Xcode 9.1.

## [0.4.0](https://github.com/xmartlabs/Bender/releases/tag/0.4.0)

* Support for Swift 4 and Xcode 9.

## [0.3.0](https://github.com/xmartlabs/Bender/releases/tag/0.3.0)
<!-- Released on 2017-08-17. -->

* Breaking changes:
  * Constructor of `LayerSize`.
  * Constructor of `Network` class.
  * `Network` static method for loading a graph from TensorFlow.
  * `Network` `run` method.
  * `Converter` protocol definition.

## [0.2.0](https://github.com/xmartlabs/Bender/releases/tag/0.2.0)
<!-- Released on 2017-08-09. -->

* Adds Cocoapods & Carthage support.
* Adds [MetalPerformanceShadersProxy](https://github.com/xmartlabs/MetalPerformanceShadersProxy) in order to allow compilation on simulators.
* Adds support for Concat layer.
* Removes "convSize" constructor parameter from ResidualLayer.
* Fixes ordering issue while optimizing TensorFlow graph.
* Fixes memory usage issue.
* Fixes ConvTranspose layer.
* Adds optional dispatchQueue where to run.

## [0.1.0](https://github.com/xmartlabs/Bender/releases/tag/0.1.0)
<!-- Released on 2017-06-05. -->

* This is the initial version.

[xmartlabs]: https://xmartlabs.com

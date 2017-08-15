# Fast Fourier Transform
Fast Fourier Transform (FFT) implementation for Unity.

To use it, just call FastFourierTransform.FFT([your parameter here]).

Since Unity has no native support for System.Numerics, Accord.Net, a very powerful tool for general AI purposes, was used for the complex type. Accord also has an FFT implementation, though it is limited by a maximum input size of Mathf.Pow(2, 14).

You can find more about Accord.Net here: https://github.com/accord-net/framework and here http://accord-framework.net/.

For compatibility reasons, Accord.Net 3.5 (net35 folder) was used and to effectively build you might need the System.ComponentModel.DataAnnotations.dll which can be found here: http://originaldll.com/file/system.componentmodel.dataannotations.dll/10126.html

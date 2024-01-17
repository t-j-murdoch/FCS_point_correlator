
<html>
<head>
</head>
<body>
<H1>FoCuS-point</H1>

<H4>Python TCSPC (Time Correlated Single Photon Counting) FCS (Fluorescence Correlation Spectroscopy)  data visualiser. </H4>

<p>This is modified from the source code repository for FoCuS-point software. The primary changes are to the correlation.py and fib4.c for compatibility with numpy 1.26.3. It is likely that fib4.pyx will need to be recompiled for Linux and OSX. For full details of the original project please refer to the project website: <a href="http://dwaithe.github.io/FCS_point_correlator/">FoCuS-point project page.</a><p>

<p> To install in a new conda environment:
<ol> conda install numpy scipy matplotlib lmfit git </ol>
<ol> pip install git+https://github.com/t-j-murdoch/FCS_point_correlator/ —upgrade (should work for all OS as long as the dependencies are met).</ol>
<ol> To run: python -m focuspoint.FCS_point_correlator</ol>

<p>NB -only the tttr2xfcs in correlation_methods.py as used in https://github.com/t-j-murdoch/sgFCS_PTU has been tested</p>

</body>
</html>

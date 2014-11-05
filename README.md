MWFFT2
======

Robust alignment of chromatograms by Moving Window Fast Fourier Transfrom


Usage
======

1. Clone this project with git
2. Start MATLAB and change the working dir to the folder of project
3. Run the following code in MATLAB command window to see alignment result

```matlab
      load demo
      w=70
      [xa,matrix,sr] = mwfft2(x,r,w);
      plot(x,'r');hold on;plot(r,'b');plot(xa,'g')
      legend('to align','reference','aligned');
```

A laser pulse with FWHM on the femtosecond scale appears as an impulse response on a digital oscilloscope. Typically a digital oscilloscope can only sample 4-5 data points on any pulse. This presents problems when interpolation algorithms such as spline or sinx/x are used to fit the data, the results plots are very poor. Thankfully, because the shape of the laser pulses are known, the known shape can be used as a guide for fitting. This results in significant increases in accuracy. This program (ILA) fits pulses using this technique of fitting the data to a known shape.

![ILA - 1](https://github.com/user-attachments/assets/f3b565dd-8d19-4dbd-a195-2a1d46ae8734)
![ILA - 2](https://github.com/user-attachments/assets/f221957c-e9c4-4a0e-9426-0d25cba28ee0)
![ILA - 3](https://github.com/user-attachments/assets/67e1e2fe-3958-4a19-b8f2-5aaa4136853a)

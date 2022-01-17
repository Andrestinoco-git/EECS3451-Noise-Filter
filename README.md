# EECS3451-Noise-Filter
Made for EECS3451 course to filter out a noisy signal using matlab code!
First, noise is analyzed in frequency domain (Figure 2). After getting the peak frequencies, 
two  notch filters are designed; one for each peak. The convolution of the individual filters, 
in time  domain, returned a combined filter whose frequency response is shown in Figure 3. When
the noisy signal is passed through this filter (convolution again!), noise is eliminated and  a 
clean signal is returned.

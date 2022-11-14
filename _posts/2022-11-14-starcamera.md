# Finding outliers in GRACE star camera data with deep learning

GRACE star camera data is published in terms of quaternions, and they look like this:

![scaaRL03_03080Blog](https://user-images.githubusercontent.com/50994293/201694137-32d6f7d5-d4ea-48b6-b2f8-bb9c35e1bd6c.png)

Which is difficult to detect.

Star camera data are available for 15 years, in columns format.

In deep learning, I formulate this problem as outlier detection in time series. 

The outliers are in fine frequency domain. 

Sigve Haug suggested to do a Fourier transform to get a 2D picture for daily time sereis and then apply deep learning to detect outliers.


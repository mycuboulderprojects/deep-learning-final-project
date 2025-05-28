# <span style="color: royalblue;">Introduction to Deep Learning - Final Project</span>

<span style="font-size: 18px; font-weight: bold; color: royalblue;">Classifying Digits From EEG Brain Signals</span>

<span style="font-size: 14px; font-weight: bold; color: royalblue;">Author: David Weber, 2025 Summer 1 Session</span>

<span style="font-size: 16px; font-weight: bold; color: royalblue;">Introduction:</span>

For my **Introduction to Deep Learning** final project, I took inspiration from an article I read in my **Ethical Issues in Computing Applications** class. The article centered on the use of brain-computer interfaces such as Neuralink, but it also mentioned that researchers were looking into non-invasive forms of brain-computer interfaces. I believe artificial intelligence will greatly benefit humanity through medical technology advances, so I wanted to do a final project related to a brain interaction using EEG data.

In my research I came across a site of titled **The "MNIST" of Brain Digits** where data was collected from a subject who was shown a digit and thought about it for about 2 seconds. This seemed like a perfect topic to do a final project on. The site has 4 different datasets, one of which was from using the **EPOC X - 14 Channel Wireless EEG Headset**. I chose this dataset because the device has the most channels compared to the other devices.

The data is from a large number of events with a comma separated set of values representing time-series amplitudes of the signal. This data is collected across 14 different channels, each collecting neural activity from different areas of the brain.

My goal with this project is to use this data to predict which digit the subject was shown (and thought) about. Because of how the data is structured, I believe using both convolutional neural networks (**CNN**) and recurrent neural networks (**RNN**) will be beneficial.

# AIC23-Codec-DSK6713
Using  AIC23 Codec with DSK6713 development board

The DSK6713 development board features a stereo audio input and output integrated circuit, which is the TLV320AIC23 codec. The codec performs analog-to-digital conversion of the audio input and digital-to-analog conversion for the output.

According to Texas Instruments, the codec manufacturer, the TLV320AIC23 is a high-performance stereo audio codec. Both its ADC and DAC converters use multibit sigma-delta technology that integrates built-in digital oversampling interpolation filters. It allows conversion word lengths of 16, 20, 24, and 32 bits, with sampling frequencies from 8 kHz to 96 kHz.
The integrated circuit also features an analog bypass configuration and a stereo headphone amplifier with analog volume control and mute. The headphone amplifier is capable of delivering 30 mW per channel into 32 Ω. The analog bypass allows the use of the stereo line inputs and the headphone amplifier with analog volume control, completely bypassing the codec. The AIC23 features an integrated microphone amplifier with adjustable gain from 1 to 5 and a programmable microphone gain amplifier of 0 dB or 20 dB. Some of the features mentioned can be configured in the codec registers. Figure 1 shows the block diagram of the codec.
 
<img width="350" height="500" alt="image" src="https://github.com/user-attachments/assets/c57c5296-3c86-4011-bae2-647b4ec92afb" />

* AIC23 registers
Figure 2 below lists the AIC23 codec registers that allow you to configure it or obtain information.
<img width="500" height="350" alt="image" src="https://github.com/user-attachments/assets/0fd232fc-b120-4d15-a520-eb61897577b0" />


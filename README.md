# Modulation-Classification-Using-CNN
In this study, we use various signal constellation diagrams to classify signal modulations into 8 modulations type namely, Binary Phase-Shift Key-ing (BPSK),4-Pulse Amplitude Modulation (4PAM),Quadrature Phase-Shift Keying (QPSK),Gaussian Frequency Shift Keying(GFSK),Eight Phase-Shift Keying (8PSK),16 Quadrature Amplitude Modulation (16QAM),Continuous Phase Frequency Shift Keying (CPFSK) and 64 Quadrature Amplitude Modulation (64QAM) using convolutional neural network architecture, to maximise the accuracy of a model. Two signal constellation diagrams have been evaluated:
1. Constellation Diagram: A constellation diagram is a two-dimensional scatter diagram that shows how a signal is modulated by a digital modulation scheme. It displays the signal as a scatter diagram in the complex plane at symbol sampling instants, providing a binary image.
2. Gray Image: A gray image provides the impact of multiple samples on a given pixel. The obtained image dataset from raw signal is then feed to a basic CNN model as input, the layers of the architecture is mentioned in the diagram Figure2.

The obtained image dataset from raw signal is then feed to a basic CNN model as input. The layers of the architecture are mentioned in the below diagram :
![image](https://github.com/SirxChinni/Modulation-Classification-Based-on-Signal-Constellation-Diagrams-and-Deep-Learning/assets/118927425/9fcecc78-7c0d-47e7-8428-615178c520ca)

The implementation is done in Python using Theano/Keras with Google Colab.

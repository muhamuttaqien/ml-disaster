# ml-disaster

This repository explores the application of Long Short-Term Memory (LSTM) networks for building a tsunami detection system. The current implementation utilizes an observation window (sequence_length) of 20.

## LSTM Models

### Univariate LSTM Models
1. **Vanilla LSTM**: Basic LSTM model with a single layer.
2. **Stacked LSTM**: LSTM with multiple layers stacked one after the other.
3. **Bidirectional LSTM**: Processes data in both forward and backward directions.
4. **CNN LSTM**: Combines Convolutional Neural Network (CNN) layers with LSTM layers.
5. **ConvLSTM**: Integrates convolution operations within the LSTM cells.

### Multivariate LSTM Models
1. **Multiple Input Series**: Processes more than one data sequence as input.
2. **Multiple Parallel Series**: Multiple series processed in parallel as separate inputs.

### Multi-Step LSTM Models
1. **Vector Output Model**: Outputs a vector of multiple steps at once.
2. **Encoder-Decoder Model**: Uses an encoder LSTM layer followed by a decoder LSTM layer to predict sequences.

### Multivariate Multi-Step LSTM Models
1. **Multiple Input Multi-Step Output**: Takes multiple inputs and predicts multiple future steps.
2. **Multiple Parallel Input and Multi-Step Output**: Multiple parallel inputs used to predict multiple future outputs simultaneously.
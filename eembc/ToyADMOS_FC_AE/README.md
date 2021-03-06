# Sources
* Dataset
    * [https://zenodo.org/record/3351307](https://zenodo.org/record/3351307)
    * See https://arxiv.org/pdf/1908.03299.pdf for details. Individual patterns were downloaded and used - page 2, figure 2.
    * We have trained and tested the model with the toy car data, case 1 only.
* Model Topology
    * [http://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds](http://dcase.community/challenge2020/task-unsupervised-detection-of-anomalous-sounds)
    * [https://github.com/y-kawagu/dcase2020_task2_baseline](https://github.com/y-kawagu/dcase2020_task2_baseline)
* Spectrogram Characteristics
    * Front-end: [https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/microfrontend](https://github.com/tensorflow/tensorflow/tree/master/tensorflow/lite/experimental/microfrontend)
    * Configuration: window=64ms, stride=32ms, bins=128, Upper frequency limit=24KHz, use only 5 center time windows

# Performance (floating point model) 
* Accuracy
    * 90.0%
* AUC
    * .927

# Performance (quantized tflite model) 
* Accuracy
    * 88.1%
* AUC
    * .87
# Vis-Quant

Visualizing DNN Quantization effect on Network.

Vis-quant gives feature map visualization for quantized network with weight quantization.

① Functionality1: Bit-width selection of weight quantization.

[![Functionality1](https://img.youtube.com/vi/Rlf3xSjMDJU/0.jpg)](https://www.youtube.com/watch?v=Rlf3xSjMDJU)


② Functionality2: Batchnorm shift-term correction with double, triple, .. terms.

[![Functionality1](https://img.youtube.com/vi/43TykyoUxG4/0.jpg)](https://www.youtube.com/watch?v=43TykyoUxG4)

## Running

Clone or download this repository:

```bash
git clone https://github.com/HanByulKim/vis-quant
```

Install the dependencies:

```bash
npm install
```

Run vis-quant:

```bash
npm run dev
```

Navigate to [localhost:5000](https://localhost:5000).


If port:5000 doesn't work, change port and run again:

```bash
PORT=8000 npm run dev
```

Navigate to [localhost:8000](https://localhost:8000).

## Citation

Our project is based on the codes of CNN-Explainer.

```bibTeX
@article{wangCNNExplainerLearning2020,
  title = {{{CNN Explainer}}: {{Learning Convolutional Neural Networks}} with {{Interactive Visualization}}},
  shorttitle = {{{CNN Explainer}}},
  author = {Wang, Zijie J. and Turko, Robert and Shaikh, Omar and Park, Haekyu and Das, Nilaksh and Hohman, Fred and Kahng, Minsuk and Chau, Duen Horng},
  journal={IEEE Transactions on Visualization and Computer Graphics (TVCG)},
  year={2020},
  publisher={IEEE}
}
```

If you find our project helpful, please consider to cite our project

```bibTeX
@article{VisQuant2021,
  title = {{{Vis-Quant}}: {{Visualizing DNN Quantization effect on Network.}},
  shorttitle = {{{Vis-Quant}}},
  author = {Han-Byul Kim and Euntae Choi},
  project={2021SNU_infovis},
  year={2021}
}
```

## License

The software is available under the [MIT License](https://github.com/HanByulKim/vis-quant).

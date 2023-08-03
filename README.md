### Deep learning for histopathological assistance: a classification-segmentation model to detect micrometastases in breast cancer

Deep Learning algorithms for detecting micrometastasis in breast cancer have the potential of gener-
ating good results when used complementarily to improve the efficiency of pathologists’ routines. An
analysis of the literature indicates that the models still need to improve their performance in identifying
micrometastases and tumor cells. In the case of isolated tumor cells, the detection rates were below
40%. There are also opportunities to improve on false positive rates, since many models still detect
nerves or contaminations as false micrometastases. In this study, we investigated the implementation
of a two-layer neural network model. The first network is responsible for classifying metastases in an
image, and the second is responsible for performing the segmentation of tumor cells, analyzing the size
of the metastatic region, and generating the final result for micrometastasis, metastasis, or negative
metastasis. This repository is the first investigation of the proposed method. As partial results, we achieved
an AUC = 0.998 for the classification task at the patch level and 𝐼𝑜𝑈 − 𝑆𝑐𝑜𝑟𝑒 ∶ 0.5434 e 𝐹 1 − 𝑆𝑐𝑜𝑟𝑒 ∶ 0.64818 for
the segmentation task.

The final result still (slide level) need to be improved.

##### Links:
- [Pipilene](https://github.com/gabrielakuhn/claseg/files/11781803/pipilene.pdf)
- [Dissertação](http://www.repositorio.jesuita.org.br/handle/UNISINOS/12439)
- [Artigo SBCAS 2023](https://sol.sbc.org.br/index.php/sbcas/article/view/25307)

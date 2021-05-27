# Representation Shift
This is the official repo for the paper ["Measuring Domain Shift for Deep Learning in Histopathology"](https://ieeexplore.ieee.org/document/9234592).

## Requirements
For calculating the representation shift using Wasserstein distance, the implementation from `scipy` was used.
To run example code, the following python libs are needed: `numpy`, `scipy`, `torch`, `torchvision`.

## Example code
In `example_repr_shift_calc.ipynb` we show an example usage, where a pretrained Resnet18 model is used, and the representation shift is calculated for both in-distribution and out-of-distribution data. This example can easily be extended to other model architectures, and other datasets.

## Cite
```
@article{stacke_2021,
	title = {Measuring {Domain} {Shift} for {Deep} {Learning} in {Histopathology}},
	volume = {25},
	issn = {2168-2208},
	doi = {10.1109/JBHI.2020.3032060},
	number = {2},
	journal = {IEEE Journal of Biomedical and Health Informatics},
	author = {Stacke, Karin and Eilertsen, Gabriel and Unger, Jonas and Lundström, Claes},
	month = feb,
	year = {2021},
}

```

# zan.initializer

Sample to show how input dim(input_dim for FC layer, for CNN, it's prod(tensor.shape[1:])) reciprocal could be used for initial NN weights:dragon:

Sometimes more effective than xavier initializer in my experiments if without BatchNorm layers inside the network.

```
@misc{zan2017initializer,
  title={Input Dimension Reciprocal for Effective Weight Initialization},
  author={Huang, Zan},
  year={2017},
  publisher={GitHub},
  howpublished={\url{https://github.com/pmixer/zan.initializer}},
}
```

![](https://camo.githubusercontent.com/1b8f04b8ff248ffd132c13343858d070c4805406bbd4c4651f9b27e9c2f01a58/68747470733a2f2f494e464f524d534a6f432e6769746875622e696f2f6c6f676f732f494e464f524d535f4a6f75726e616c5f6f6e5f436f6d707574696e675f4865616465722e6a7067) 
# Forecasting Urban Traffic States with Sparse Data Using Hankel Temporal Matrix Factorization

This archive is distributed in association with the [INFORMS Journal on Computing](https://pubsonline.informs.org/journal/ijoc) under the [MIT License](LICENSE).

The software and data in this repository are a snapshot of the software and data that were used in the research reported on in the paper Forecasting Urban Traffic States with Sparse Data Using Hankel Temporal Matrix Factorization by X. Chen, X.-L. Zhao and C. Cheng.

## Cite

To cite the contents of this repository, please cite both paper and this repo, using their respective DOIs.

https://doi.org/10.1287/ijoc.2022.0197

https://doi.org/10.1287/ijoc.2022.0197.cd

Below is the BibTex for citing this snapshot of the repository.

```
@misc{Chen2024,
    author =    {X. Chen, X.-L. Zhao and C. Cheng},
    publisher = {INFORMS Journal on Computing},
    title =     {Forecasting Urban Traffic States with Sparse Data Using Hankel Temporal Matrix Factorization},
    year =      {2024},
    doi =       {10.1287/ijoc.2022.0197.cd},
    url =       {https://github.com/INFORMSJoC/2022.0197},
    note =      {Available for download at https://github.com/INFORMSJoC/2022.0197},
}
```

## Description

[Uber movement project](https://movement.uber.com/) provides data and tools for cities to more deeply understand and address urban transportation problems and challenges. Uber movement speed data measure hourly street speeds across a city (e.g., [Seattle](https://movement.uber.com/explore/seattle/speeds)) to enable data-driven city planning and decision making. These data are indeed multivariate time series with N road segments and T time steps (hours), and are featured as high-dimensional, sparse, and nonstationary. To overcome the challenge created by these complicated data behaviors, we propose a temporal matrix factorization framework for multivariate time series forecasting on high-dimensional and sparse Uber movement speed data.

## Replicating the Experiments

This HTMF algorithm is implemented using the `NumPy` package in Python, which can be easily converted into the GPU version when using the `CuPy` package. To reproduce the experiments in our manuscript, please using Jupyter Notebook to run `codes/HTMF.ipynb`.
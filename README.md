This repo contains code to reproduce the paper: Neural sampling from cognitive maps enables goal-directed imagination and planning

Citation:
@article{lin2025neural,
  title={Neural sampling from cognitive maps supports goal-directed planning and imagination},
  author={Lin, Hui and Yang, Yukun and Zhao, Rong and Pezzulo, Giovanni and Maass, Wolfgang},
  journal={bioRxiv},
  pages={2025--05},
  year={2025},
  publisher={Cold Spring Harbor Laboratory}
}

### Execution
This project is setup with [pixi](https://pixi.prefix.dev/latest/).

```sh
curl -fsSL https://pixi.sh/install.sh | sh

pixi install

# if you only have CPU
pixi shell
# or, if you have an nvidia GPU
pixi shell -e gpu

jupyter notebook
```
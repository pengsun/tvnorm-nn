# tvnorm-nn
Total Variation Norm as Torch 7 `nn` module. 

## Intro
Calculate Total Variation Norm (TODO: ref?). Expose a module `nn.tvnorm` that expects tensor:
```
input size: B, C, H, W
output size: B, C
```
where
```
B: batch size
C: #channels/#feature maps
H: image height
W: image width
```

Only support CUDA tensor, `cudnn` required.

## Install
git clone this repo, cd to the directory, then use command
```
luarocks make
```
to complete installation.

# gifs_distributed_relaying_PB

Animations accompanying the paper: 8 robots moving to a target formation through terrain with drag patches.

Each row is one target formation. The left column shows the baseline with the PB operator switched off (u = 0, inner PI loop only). The right column shows the trained distributed PB controller.

| Target | Without PB | With PB |
|:---:|:---:|:---:|
| **Direct**: formation translated only | <img src="figures/direct_noPB.gif" width="400"> | <img src="figures/direct_PB.gif" width="400"> |
| **Flip**: formation rotated by π | <img src="figures/flip_noPB.gif" width="400"> | <img src="figures/flip_PB.gif" width="400"> |
| **Offset**: formation shifted right and rotated by π/2 | <img src="figures/offset_noPB.gif" width="400"> | <img src="figures/offset_PB.gif" width="400"> |

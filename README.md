# Humanoid Self-Other Distinction

Official implementation of the paper **"Proprioceptive-Visual Correspondence Enables Self-Other Distinction in Humanoid Robots"**.

<p align="left">
    <a href="https://arxiv.org/abs/2606.13222" target="_blank"><img alt="arXiv" src="https://img.shields.io/badge/arXiv-2606.13222-red?logo=arxiv" height="25" /></a>
    <a href="https://euron-zc.github.io/humanoid-self-model/" target="_blank"><img alt="Project page" src="https://img.shields.io/badge/Project-Page-blue" height="25" /></a>
</p>

<div align="center">
    <br>
    <div style="text-align: center;">
        Yurun Chen<sup>1,2</sup> &emsp;
        Tianyuan Gao<sup>3</sup> &emsp;
        Yizhong Ge<sup>1</sup> &emsp;
        Shikun Ban<sup>4</sup>
        <br>
        Yizhou Wang<sup>3</sup> &emsp;
        Hongkai Xiong<sup>2,5&#9993;</sup> &emsp;
        Wenjun Zeng<sup>1,6&#9993;</sup> &emsp;
        Wentao Zhu<sup>1,6&#9993;</sup>
        <br>
        <br>
        <p style="text-align: center; margin-bottom: 0;">
            <sup>1</sup>Eastern Institute of Technology, Ningbo &emsp;
            <sup>2</sup>Shanghai Jiao Tong University &emsp;
            <sup>3</sup>Peking University
            <br>
            <sup>4</sup>Carnegie Mellon University &emsp;
            <sup>5</sup>East China Normal University &emsp;
            <sup>6</sup>Ningbo Institute of Digital Twin
        </p>
        <p style="text-align: center; margin-bottom: 0;">
            &#9993; Corresponding authors
        </p>
    </div>
</div>

<hr>

## Overview

Distinguishing self from others is a prerequisite for embodied intelligence. Before a humanoid robot can imitate, coordinate, or avoid nearby bodies, it must answer a basic question: **Which body is mine?**

> From several visible bodies, the robot must select the candidate whose configuration matches its proprioceptive state, without identity labels or prior knowledge of its morphology.

We study this problem through proprioceptive-visual correspondence. Given proprioceptive states and visual observations, the framework identifies the robot's own body among humans or similar humanoids, then uses the resulting self-observations to learn a kinematics-free 3D occupancy self-model.

### Framework

![Pipeline overview](static/images/fig1b.png)

The pipeline has two stages:

1. **Self-other distinction** matches proprioceptive states to visual observations to identify the robot's own body.
2. **Self-modeling** learns a 3D body occupancy field from the distinguished self-observations.

## News

- [2026.06] Code coming soon.

## Citation

If you find this work useful, please consider citing:

```bibtex
@misc{chen2026proprioceptivevisualcorrespondenceenablesselfother,
      title={Proprioceptive-visual correspondence enables self-other distinction in humanoid robots}, 
      author={Yurun Chen and Tianyuan Gao and Yizhong Ge and Shikun Ban and Yizhou Wang and Hongkai Xiong and Wenjun Zeng and Wentao Zhu},
      year={2026},
      eprint={2606.13222},
      archivePrefix={arXiv},
      primaryClass={cs.RO},
      url={https://arxiv.org/abs/2606.13222}, 
}
```

## Contact

For questions or discussions, please contact:
- Yurun Chen: euron.zc@gmail.com

## License

License will be specified upon code release.

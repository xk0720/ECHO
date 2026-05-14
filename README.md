[//]: # (# ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation)

## ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation

[Xiangyu Kong<sup>1,2</sup>](https://github.com/xk0720/ECHO), &nbsp; [Xiaoyu Jin<sup>2</sup>](https://github.com/xk0720/ECHO), &nbsp; [Yihan Pan<sup>2</sup>](https://github.com/xk0720/ECHO), &nbsp; [Haoqin Sun<sup>3</sup>](https://github.com/xk0720/ECHO), &nbsp; [Hengde Zhu<sup>4</sup>](https://github.com/xk0720/ECHO), &nbsp; [Xiaoming Xu<sup>2</sup>](https://github.com/xk0720/ECHO), &nbsp; [Xiaoming Wei<sup>2</sup>](https://github.com/xk0720/ECHO), &nbsp; [Lu Liu<sup>1</sup>](https://github.com/xk0720/ECHO), &nbsp; [Siyang Song<sup>1</sup>](https://github.com/xk0720/ECHO) <br>
<sup>1</sup>University of Exeter &nbsp; <sup>2</sup>Meituan &nbsp; <sup>3</sup>Nankai University &nbsp; <sup>4</sup>Tongji University &nbsp;

[//]: # (&nbsp; &nbsp;)

[![arXiv](https://img.shields.io/badge/arXiv-2603.17427-b31b1b?logo=arxiv)](https://arxiv.org/abs/2603.17427)
[![Project Page](https://img.shields.io/badge/Project-Page-green)](https://xk0720.github.io/ECHO/)

### Abstract
In natural face-to-face interaction, participants seamlessly alternate between speaking and listening, producing facial behaviors (FBs) that are finely informed by long-range context and naturally exhibit contextual appropriateness and emotional rationality. Interactive Head Generation (IHG) aims to synthesize lifelike avatar head video emulating such capabilities. Existing IHG methods typically condition on dual-track signals (i.e., human user's behaviors and pre-defined audio for avatar) within a short temporal window, jointly driving generation of avatar's audio-aligned lip articulation and non-verbal FBs. However, two main challenges persist in these methods: (i) the reliance on short-clip behavioral cues without long-range contextual modeling leads them to produce facial behaviors lacking contextual appropriateness; and (ii) the entangled, role-agnostic fusion of dual-track signals empirically introduces cross-signal interference, potentially compromising lip-region synchronization during speaking. To this end, we propose ECHO, a novel IHG framework comprising two key components: a Long-range Contextual Understanding (LCU) component that facilitates contextual understanding of both behavior-grounded dynamics and linguistic-driven affective semantics to promote contextual appropriateness and emotional rationality of synthesized avatar FBs; and a block-wise Spatial-aware Decoupled Cross-attention Modulation (SDCM) module, that preserves self-audio-driven lip articulation while adaptively integrating user contextual behavioral cues for non-lip facial regions, complemented by our designed two-stage training paradigm, to jointly enhance lip synchronization and visual fidelity. Extensive experiments demonstrate the effectiveness of proposed components and ECHO's superior IHG performance.

### Citation
```
@article{kong2026echo,
  title={ECHO: Towards Emotionally Appropriate and Contextually Aware Interactive Head Generation},
  author={Kong, Xiangyu and Jin, Xiaoyu and Pan, Yihan and Sun, Haoqin and Zhu, Hengde and Xu, Xiaoming and Wei, Xiaoming and Liu, Lu and Song, Siyang},
  journal={arXiv preprint arXiv:2603.17427},
  year={2026}
}
```
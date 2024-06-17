# Vivid-ZOO: Multi-View Video Generation with Diffusion Model


<p align="center">
  [<a href="https://arxiv.org/pdf/2406.08659" target="_blank"><strong>Paper</strong></a>]
  [<a href="https://hi-zhengcheng.github.io/vividzoo/" target="_blank"><strong>Project</strong></a>]
  [<a href="#citation"><strong>BibTeX</strong></a>]
</p>



https://github.com/hi-zhengcheng/vividzoo/assets/33408107/521ea013-08c8-47a8-84f1-511c31a9f1dd


While diffusion models have shown impressive performance in 2D image/video generation, diffusion-based Text-to-Multi-view-Video (T2MVid) generation remains underexplored. The new challenges posed by T2MVid generation lie in the lack of massive captioned multi-view videos and the complexity of modeling such multi-dimensional distribution. To this end, <b>we propose a novel diffusion-based pipeline that generates high-quality multi-view videos centered around a dynamic 3D object from text</b>. Specifically, we factor the T2MVid problem into viewpointspace and time components. Such factorization allows us to combine and reuse layers of advanced pre-trained multi-view image and 2D video diffusion models to ensure multi-view consistency as well as temporal coherence for the generated multi-view videos, largely reducing the training cost. We further introduce alignment modules to align the latent spaces of layers from the pre-trained multi-view and the 2D video diffusion models, addressing the reused layers’ incompatibility that arises from the domain gap between 2D and multi-view data. To facilitate this research line, we further contribute a captioned multi-view video dataset. Experimental results demonstrate that our method generates high-quality multi-view videos, exhibiting vivid motions, temporal coherence, and multi-view consistency, given a variety of text prompts.

## News
**[06/14/2024]** We have released paper!  
**[06/17/2024]** We have released our 4D Dataset!
## TODO
- [x] The dataset will be released soon
## 4D Dataset
If you would like to download our 4D Dataset data, please fill out this [google form](https://forms.gle/hk46ZhP9WZNWuS786), once accepted, we will send you the link to download the data. You should receive the link within one or two days.


## Acknowledgement

- [AnimateDiff](https://github.com/guoyww/AnimateDiff)
- [MVDream](https://github.com/bytedance/MVDream)
- [objaverse-1.0](https://objaverse.allenai.org/objaverse-1.0/)
- [Cap3D](https://github.com/crockwell/Cap3D)



## Citation
```
@misc{li2024vividzoo,
      title={Vivid-ZOO: Multi-View Video Generation with Diffusion Model}, 
      author={Bing Li and Cheng Zheng and Wenxuan Zhu and Jinjie Mai and Biao Zhang and Peter Wonka and Bernard Ghanem},
      year={2024},
      eprint={2406.08659},
      archivePrefix={arXiv},
}
```

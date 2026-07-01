# ImageNet-LC

This repository points to the official implementation for our paper:

**ImageNet-LC: Assessing Robustness under Localized Corruptions**  
ICPR CO 2026

ImageNet-LC is an object-centric robustness benchmark for ImageNet. Instead
of applying corruptions globally to the full image, ImageNet-LC localizes the
foreground object regions and applies corruptions only inside those regions of
interest. This enables evaluation of model robustness under more targeted,
localized visual degradations.

The benchmark includes localized corruptions such as lens flare, illumination
variation, dust and scratches, fingerprint smudges, focus shift, occlusion, and
camouflage across multiple severity levels.

## Official Code

The main code release is available here:

**https://github.com/muskanny/ImageNet-LC**

Please use the main repository for installation instructions, pipeline usage,
updates, and issue tracking.

## Citation

If you use ImageNet-LC in your work, please cite the paper:

```bibtex
@inproceedings{imagenetlc2026,
  title     = {ImageNet-LC: Assessing Robustness under Localized Corruptions},
  booktitle = {ICPR CO},
  year      = {2026}
}
```

# Gated Multi-Resolution Transfer Network for Burst Restoration and Enhancement(CVPR 2023)
### News	
Feb 27, 2023: Paper accepted to CVPR 2023


**Abstract**: 
		*Burst image processing is becoming increasingly popular in recent years. However, it is a challenging task since individual 
		burst images undergo multiple degradations and often have mutual misalignments resulting in ghosting and zipper artifacts. Existing
		burst restoration methods usually do not consider the mutual correlation and non-local contextual information among burst frames, which
		tends to limit these approaches in challenging cases. Another key challenge lies in the robust up-sampling of burst frames. The existing 
		up-sampling methods cannot effectively utilize the advantages of single-stage and progressive up-sampling strategies with conventional 
    and/or recent up-samplers at the same time. To address these challenges, we propose a novel Gated Multi-Resolution Transfer Network (GMTNet)
    to reconstruct a spatially precise high-quality image from a burst of low-quality raw images. GMTNet consists of three modules optimized for 
    burst processing tasks:	Multi-scale Burst Feature Alignment (MBFA) for feature denoising and alignment, Transposed-Attention Feature Merging
    (TAFM) for multi-frame feature aggregation, and Resolution Transfer Feature Up-sampler (RTFU) to up-scale merged features and construct a high-
    quality output image. Detailed experimental analysis on	five datasets validates our approach and sets a  state-of-the-art for burst super-resolution, 
    burst denoising, and low-light burst enhancement*.
    
## Network Architecture

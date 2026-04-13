Variational Autoencoders are a class of early generative models that have been used to make large ad-
vancements in image generation problems. Extended by conditional VAEs, these class of models are used
often for class-guided image generation. However, performance of these models is highly dependent on the
design choices involved in both the training objective and the latent representation. In this project, we
delve into how KL penalties in the training objective can be varied and how doing so impacts the quality
of image generations. We also examine various latent space representations, varying both latent distribu-
tions and dimensionality. In particular we see how the latent space performs when considering much more
complex images such as the CIFAR-10 dataset.To explore these questions, we implement and work with a
β-Conditional Variational Autencoder or a β-CVAE.

The primary contribution of this project will be to analysze the tradeoff between latent-space interpretabil-
ity and reconstruction quality in β-CVAEs for class-conditional image generation. While β-VAE models
are known to produce more structured and interpretable latent representations KL penalties, this typically
comes at the cost of reduced reconstruction fidelity.

In this work, we extend this analysis to the conditional setting and to more complex image-generation
tasks (if compute allows). We aim to characterize how these design choices interact in determining recon-
struction performance, latent organization, and the quality of generated samples.

In addition, we investigate whether increased latent capacity can mitigate the traditional tradeoff ob-
served in β-VAEs. In particular, we hypothesize that with a sufficiently expressive latent space, it may be
possible to achieve both interpretable latent spaces and high-quality image generations.


Overall, this project aims to explore latent space design choices in VAEs for image generation and how
these choices affect the balance between interpretability and generation quality.

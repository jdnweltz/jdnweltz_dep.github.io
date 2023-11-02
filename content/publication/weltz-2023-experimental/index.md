---
title: Experimental Designs for Heteroskedastic Variance
authors:
- Justin Weltz
- Tanner Fiez
- Alexander Volfovsky
- Eric Laber
- Blake Mason
- Houssam Nassif
- Lalit Jain
abstract: Most linear experimental design problems assume homogeneous variance, even though heteroskedastic noise is present in many realistic settings. Let a learner have access to a finite set of measurement vectors {{< math >}} $\\mathcal{X}\\subset \\mathbb{R}\\^d$ {{< /math >}} that can be probed to receive noisy linear responses of the form {{< math >}} $y=x^{\top}\theta^{\ast}+\eta$ {{< /math >}}. Here {{< math >}} $\theta^{\ast}\in \mathbb{R}^d$ {{< /math >}} is an unknown parameter vector, and $\eta$ is independent mean-zero $\sigma_x^2$-strictly-sub-Gaussian noise defined by a flexible heteroskedastic variance model, $\sigma_x^2 = x^{\top}\Sigma^{\ast}x$. Assuming that $\Sigma^{\ast}\in \mathbb{R}^{d\times d}$ is an unknown matrix, we propose, analyze and empirically evaluate a novel design for uniformly bounding estimation error of the variance parameters, $\sigma_x^2$. We demonstrate the benefits of this method with two adaptive experimental design problems under heteroskedastic noise, fixed confidence transductive best-arm identification, and level-set identification; proving the first instance-dependent lower bounds in these settings. Lastly, we construct near-optimal algorithms and empirically demonstrate the large improvements in sample complexity gained from accounting for heteroskedastic variance in these designs.
date: '2023-01-01'
publishDate: '2023-11-02T02:34:20.335090Z'
publication_types:
- paper-conference
publication: 'Advances in Neural Information Processing Systems, 36'
url_pdf: https://arxiv.org/pdf/2310.04390.pdf
featured: true
---


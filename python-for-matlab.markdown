---
title: Python for MATLAB users
layout: page
---

<!-- wp:paragraph -->
<p>During the majority of my academic career I used MATLAB for data analysis.  As you might expect, with ~15 years of experience, I had developed a workflow that I was fairly comfortable with.  However, MATLAB does not appear to be widely used in industry, and even within academia Python seems to be growing in popularity.  Additionally, frameworks like TensorFlow are implemented in Python.  Considering this, I decided to give switching to Python for data analysis a shot.  While there are certainly a number of useful resources available to help with this transition, I figured it might be useful to share some of the things that I have found helpful.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>I envision this page being a working document, so some of this content will be fluid for the time being.</p>
<!-- /wp:paragraph -->

<!-- wp:heading {"level":3} -->
<h3>Some (hopefully) useful resources</h3>
<!-- /wp:heading -->

<!-- wp:list -->
<ul><li><a href="https://www.anaconda.com/distribution/">Anaconda</a></li><li><a href="https://jupyter.org">Jupyter</a></li><li><a href="https://www.jetbrains.com/pycharm/">PyCharm</a></li><li><a href="http://mathesaurus.sourceforge.net/matlab-numpy.html">NumPy for MATLAB users (1)</a></li><li><a href="https://docs.scipy.org/doc/numpy/user/numpy-for-matlab-users.html">NumPy for MATLAB users (2)</a></li><li><a href="http://christopherroach.com/articles/jupyterlab-desktop-app/">Configuring JupyterLab to run in Chrome in application mode</a> (and <a href="https://github.com/BurglarBenson/Jupyter-Atom-Dark-Theme">an Atom-like theme for JupyterLab</a>)</li><li><a href="https://florianwilhelm.info/2018/11/working_efficiently_with_jupyter_lab/">Developing a JupyterLab workflow</a></li></ul>
<!-- /wp:list -->


<style type="text/css">
.image-float {
  display: block;
  margin-left: 15px;
  margin-right: 15px;
  margin-top: 15px;
  margin-bottom: 15px;
  width: 300px;
  float: right;
}
</style>

---

## Research

### Constraints on the dynamics of neural population activity

![Asymmetry](/assets/EL_IntRotProj.png){: .image-float}

Though chiefly envisioned as a tool for the restoration of function following paralysis, brain-computer interfaces (BCIs) can serve as a powerful tool for scientific discovery.  In a BCI, the *mapping*, which defines the relationship between the recorded neural activity and the effector (e.g., a computer cursor), is known. Therefore, by modifying the BCI mapping, we are able to "request" neural activity with specific properties.  My current research focuses on using BCIs to probe the dynamics of neural population activity in motor cortex.  This will allow us to better understand how the cortex carries out the computations required to guide complex behavior.

#### Related work
- **Degenhart, A.D.** et al. Constraints on the time course of neural population activity. Cosyne Abstracts, 2020.
- **Degenhart, A.D.** et al. Constraints on the time course of neural population activity. Society for Neuroscience Annual Meeting 2019.

<br>

### A stabilized brain-computer interface based on neural manifold alignment

![Asymmetry](/assets/StabilizedBCI_Align.png){: .image-float}

Recent demonstrations have provided compelling evidence of the ability of BCIs to provide functional restoration for individuals with paralysis.  However, a major barrier to the clinical adoption of BCI systems are neural recording instabilities, which can quickly lead to degradations in device performance.  To overcome this shortcoming, I, in collaboration with colleagues at Carnegie Mellon University and the University of Pittsburgh, have developed a stabilized BCI which utilizes the structure in neural population activity to improve BCI stability.

#### Related work
- **Degenhart, A.D.**\*, Bishop, W.E.\*, Oby E.R., Tyler-Kabara E.C., Chase S.M.^, Batista A.P.^, Yu B.M.^ Stabilization of a brain–computer interface via the alignment of low-dimensional spaces of neural activity. Nature Biomedical Engineering (2020). (\*,^: denotes equal contributions) <https://doi.org/10.1038/s41551-020-0542-9>

<br>

### Investigating learning using brain-computer interfaces

[Coming soon]

#### Related work
- Oby, E.R., Golub, M.D., Hennig, J.A., **Degenhart, A.D.**, Tyler-Kabara, E.C., Yu, B.M., Chase, S.M., Batista, A.B.  New neural activity patterns emerge with long-term learning.  Proceedings of the National Academy of Sciences (PNAS) (2019). <https://doi.org/10.1073/pnas.1820296116>

<br>

### Three-dimensional BCI control by individuals with upper-limb paralysis using electrocorticography

Electrocorticography (ECoG) has gained prominence as a potential source of control signals for BCIs, owing in part to its stability, relatively high spatial and temporal resolution (as compared to EEG), and minimal signal processing requirements.  As a graduate student, I assessed the ability of individuals with upper-limb paralysis to control a three-dimensional ECoG-based BCI.

#### Related work
- **Degenhart, A.D.**, et al. Remapping cortical modulation for electrocorticographic brain–computer interfaces: a somatotopy-based approach in individuals with upper-limb paralysis. Journal of Neural Engineering (2018). <https://doi.org/10.1088/1741-2552/aa9bfb>
- Wang, W., Collinger, J.L., **Degenhart, A.D.**, Tyler-Kabara, E.C., Schwartz, A.B., Moran, D.W., et al. An Electrocorticographic Brain Interface in an Individual with Tetraplegia. PLoS ONE, e55344 (2013). <https://doi.org/10.1371/journal.pone.0055344>

<br>

---  

## Methods and software

### A modular software framework for brain-computer interface research

As part of my graduate research, I led the development of a BCI software suite capable of controlling various effectors (e.g., computer cursors, prosthetic limbs) using control signals extracted from ECoG recordings in real-time.

#### Related work
- **Degenhart, A.D.**, Kelly, J.W., Ashmore, R.C., Collinger, J.L., Tyler-Kabara, E.C., Weber, D.J., & Wang, W. Craniux: A LabVIEW-Based Modular Software Framework for Brain-Machine Interface Research. Computational Intelligence and Neuroscience (2011). <https://doi.org/10.1155/2011/363565>

<br>

### Improving decoding of information from Electrocorticography recordings using Empirical Bayes

[Coming soon]


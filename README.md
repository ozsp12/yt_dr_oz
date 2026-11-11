# Dr. Oz: YouTube Companion Materials

Teaching notes, worked problems, computational notebooks, and audiovisual assets for the [Dr. Oz YouTube channel](https://www.youtube.com/@ozlsp12), by **Dr. Osvaldo L. Santos-Pereira**.

This repository brings together material on physics, mathematics, data science, and scientific computing. It supports the study of the topics presented in the videos and preserves the documents, calculations, figures, and production files associated with individual lessons. Materials are available in Portuguese and English, depending on the topic.

## Repository organisation

The collection is organised by subject, with individual folders for lessons, problems, and demonstrations.

| Directory | Contents |
|---|---|
| [`physics/`](physics/) | Classical mechanics, oscillations, quantum mechanics, and introductory material on warp-drive spacetimes. |
| [`maths/`](maths/) | Algebra, number theory, calculus, inequalities, geometry, and worked examination problems. |
| [`data_science/`](data_science/) | Data analysis, visualisation, symbolic computation, and examples using Python, SQL, DAX, and Power BI. |
| [`scientific_computing/`](scientific_computing/) | Python fundamentals, computational performance, and educational material on artificial intelligence agents. |
| [`shorts/`](shorts/) | Short-form lessons and visual material on mathematics, physics, probability, and combinatorics. |

Depending on the lesson, a folder may contain PDF notes, PowerPoint presentations, LaTeX sources, Jupyter notebooks, datasets, narration scripts, figures, audio, and rendered animations or videos. Some topics include separate language versions and assets prepared for horizontal, vertical, or square formats.

## Selected starting points

The following examples provide entry points into the collection. The subject directories above contain the remaining material.

| Topic | Materials |
|---|---|
| Conservation of angular momentum | [Spinning-chair demonstration](physics/classical_mechanics_angular_momentum_spinning_chair/) |
| Coupled motion in classical mechanics | [Block sliding on a moving wedge](physics/classical_mechanics_sliding_wedge_block/) |
| Nonlinear dynamics | [Double-pendulum model and animations](physics/classical_mechanics_harmonic_motion_double_pendulum_dynamical_system/) |
| Quantum wave-packet evolution | [Wave packet interacting with a step potential](physics/quantum_mechanics_step_barrier_tunneling/) |
| General relativity | [Introduction to warp-drive spacetimes](physics/warp_drive_introduction/) |
| Algebraic equations | [Tenth-degree equations and cyclotomic polynomials](maths/algebra_tenth_degree_cyclotomic_polynomials/) |
| Inequalities | [Cauchy–Schwarz inequality](maths/analysis_inequalities_cauchy_schwarz/) |
| Trigonometry | [ENEM tangent-function problem](maths/geometry_enem_2025_question_160/) |
| Practical data analysis | [Python, SQL, and DAX fast track](data_science/data_analyst_fast_track/) |
| Exploratory analysis | [Pricing examples with synthetic data](data_science/quick_dirty_analytics/) |
| Data visualisation | [Longitudinal data and animated time series](data_science/longitudinal_data_visualization/) |
| Symbolic computation | [Introduction to SymPy](data_science/computing_sympy_symbolic_algebra/) |
| Python programming | [Syntax, operations, and basic commands](scientific_computing/programming_lesson_01_python_from_scratch/) |
| Computational performance | [pandas and NumPy comparison](scientific_computing/algorithms_complexity_analysis_pandas_vs_numpy/) |
| Artificial intelligence | [Introduction to AI agents](scientific_computing/agents_artificial_intelligence_agents/) |
| Short-form physics | [Klein–Gordon equation](shorts/phys_quantum_mech_klein_gordon_equation/) |

## Using the materials

For reading and viewing, open the relevant subject directory and select a lesson. Consult its local README when available; some lessons also provide a direct link to the corresponding video. PDFs, slides, and exported media can be downloaded individually.

To work with a local copy of the collection:

```bash
git clone --depth 1 https://github.com/ozsp12/yt_dr_oz.git
cd yt_dr_oz
```

Open Python notebooks in JupyterLab or another notebook editor using a Python 3 kernel. Consult each notebook's import cells and accompanying notes for its dependencies. When a notebook uses relative file paths, run it from its own directory so that the accompanying datasets and figures can be found. Dependencies vary by lesson; the repository does not currently provide a single environment specification for the entire collection.

Editable presentations use the `.pptx` format, and the Power BI example includes a `.pbix` file. LaTeX sources and rendered PDFs are available for selected topics. The files supplied in each folder determine which parts of a lesson can be edited or recomputed.

## Corrections and contributions

To report a mathematical, computational, or editorial issue, [open an issue](https://github.com/ozsp12/yt_dr_oz/issues) identifying the lesson folder and the relevant equation, notebook cell, slide, or file. For computational problems, include the input and environment details needed to reproduce the result. Proposed corrections can also be submitted through a pull request.

## Author

**Dr. Osvaldo L. Santos-Pereira**

<a href="mailto:olsp@if.ufrj.br">✉</a> **Email:** [olsp@if.ufrj.br](mailto:olsp@if.ufrj.br)  
<a href="https://ozsp12.github.io/">🌐</a> **Academic webpage:** [https://ozsp12.github.io/](https://ozsp12.github.io/)  
<a href="http://lattes.cnpq.br/6730251976463283">🎓</a> **Lattes:** [http://lattes.cnpq.br/6730251976463283](http://lattes.cnpq.br/6730251976463283)  
<a href="https://orcid.org/0000-0003-2231-517X"><img src="https://cdn.simpleicons.org/orcid/A6CE39" height="22" alt="ORCID" align="absmiddle"></a> **ORCID:** [https://orcid.org/0000-0003-2231-517X](https://orcid.org/0000-0003-2231-517X)  
<a href="https://scholar.google.com/citations?user=HIZp0X8AAAAJ&amp;hl=en"><img src="https://cdn.simpleicons.org/googlescholar/4285F4" height="22" alt="Google Scholar" align="absmiddle"></a> **Google Scholar:** [https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en](https://scholar.google.com/citations?user=HIZp0X8AAAAJ&hl=en)  
<a href="https://www.researchgate.net/profile/Osvaldo-Santos-Pereira"><img src="https://cdn.simpleicons.org/researchgate/00CCBB" height="22" alt="ResearchGate" align="absmiddle"></a> **ResearchGate:** [https://www.researchgate.net/profile/Osvaldo-Santos-Pereira](https://www.researchgate.net/profile/Osvaldo-Santos-Pereira)  
<a href="https://github.com/ozsp12"><img src="https://cdn.simpleicons.org/github/888888" height="22" alt="GitHub" align="absmiddle"></a> **GitHub:** [https://github.com/ozsp12](https://github.com/ozsp12)  
<a href="https://br.linkedin.com/in/ozsp12">in</a> **LinkedIn:** [https://br.linkedin.com/in/ozsp12](https://br.linkedin.com/in/ozsp12)  
<a href="https://substack.com/@olsp1982"><img src="https://cdn.simpleicons.org/substack/FF6719" height="22" alt="Substack" align="absmiddle"></a> **Substack:** [https://substack.com/@olsp1982](https://substack.com/@olsp1982)  
<a href="https://medium.com/@ozsp12"><img src="https://cdn.simpleicons.org/medium/888888" height="22" alt="Medium" align="absmiddle"></a> **Medium:** [https://medium.com/@ozsp12](https://medium.com/@ozsp12)  
<a href="https://www.youtube.com/@ozlsp12"><img src="https://cdn.simpleicons.org/youtube/FF0000" height="22" alt="YouTube" align="absmiddle"></a> **YouTube:** [https://www.youtube.com/@ozlsp12](https://www.youtube.com/@ozlsp12)  
<a href="https://x.com/ozsp12"><img src="https://cdn.simpleicons.org/x/888888" height="22" alt="X" align="absmiddle"></a> **X:** [https://x.com/ozsp12](https://x.com/ozsp12)

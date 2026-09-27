<p align="center">
  <a href="https://soilie3d.com">
    <img src="https://raw.githubusercontent.com/soilie/.github/main/assets/soilie-mark.webp" width="104" height="104" alt="SOILIE-3D: a chair inside a thought bubble">
  </a>
</p>

<h1 align="center">SOILIE-3D</h1>
<p align="center"><strong>Science of Imagination Lab Imagination Engine 3D</strong></p>
<p align="center">From remembered relationships to imagined rooms.</p>

<p align="center">
  <a href="https://soilie3d.com">Website</a> &nbsp;·&nbsp;
  <a href="https://soilie3d.com/research">Research</a> &nbsp;·&nbsp;
  <a href="https://soilie3d.com/engine">Scene engine</a> &nbsp;·&nbsp;
  <a href="https://github.com/soilie/SOILIE-3D">Source code</a>
</p>

---

### A model of spatial imagination

Can a new room be constructed from remembered relationships rather than recalled as a whole?

SOILIE-3D investigates this question with an explicit, procedural model. It treats measurements from labelled RGB-D observations as a compact relational memory, then recombines those relationships to construct new indoor scenes. The intermediate data, placement rules, and rendered outputs can be inspected alongside the results.

### From observations to scenes

| Observe | Relate | Construct |
| :--- | :--- | :--- |
| Extract labelled objects and spatial measurements from colour-and-depth observations. | Combine supported object triplets, distances, angles, and size estimates. | Place objects, construct the room, and render the resulting arrangement. |

Recency sequences show objects appearing in turn, with earlier objects fading as new ones are introduced. This is a modelling choice motivated by visual-imagination research, not a validated simulation of human experience.

### Explore the project

- **[Methods and comparisons](https://soilie3d.com/research)**: how the model works, what the evaluations measure, and their limitations.
- **[Data archive](https://soilie3d.com/data)**: research data, object assets, and scene outputs.
- **[Public gallery](https://soilie3d.com/gallery)**: scenes shared through the website.
- **[Code and setup](https://github.com/soilie/SOILIE-3D)**: the Python and Blender implementation, installation instructions, and development history.

### Origins and contributors

The project originated in the **[Science of Imagination Lab](http://scienceofimagination.pbworks.com/w/page/15236327/FrontPage)** at Carleton University in Ottawa, Canada.

See the **[SOILIE-3D contributors](https://soilie3d.com/team)** for project roles and contact details.

Maintained by **[Mike Cichonski](https://github.com/mikecichonski)**. Questions about the implementation and reproducible bug reports are welcome in the **[issue tracker](https://github.com/soilie/SOILIE-3D/issues)**.

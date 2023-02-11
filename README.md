# d3-force-registry
A curated compilation of plugins and all-things related to [d3-force](https://github.com/d3/d3-force).

Please get in touch for any additions/corrections to this list. And as always, use the force!

## Force Plugins

| Plugin | Description | Code | Examples |
|:---:|---|:---:|---|
| [d3.bboxCollide](https://www.npmjs.com/package/d3-bboxCollide) | Repelling force that prevents rectangular nodes from overlapping with each other. Great for avoiding label overlaps. | [d3-bboxCollide](https://github.com/emeeks/d3-bboxCollide) | <ul><li>[Guitar hero](https://bl.ocks.org/emeeks/b562c2c449ee30ec577f2d8339b2ce1c)</li><li>[Word clouds](https://bl.ocks.org/emeeks/19a1d77fc6ad812faedb648218b7ad60)</li></ul> |
| [d3.forceAttract](https://www.npmjs.com/package/d3-force-attract) | Spring-like force to attract nodes to a particular *<x,y>* point. | [d3-force-attract](https://github.com/ericsoco/d3-force-attract) | <ul><li>[Mouse following](https://bl.ocks.org/ericsoco/7eebab15da4bb1040977da508aebbff6)</li><li>[Multiple attraction](https://bl.ocks.org/ericsoco/6e0573860e7f6655cee885d8b1b84065)</li></ul> |
| [d3.forceBounce](https://www.npmjs.com/package/d3-force-bounce) | Elastic collision force between nodes. Useful to simulate natural collisions between circular objects that conserve energy and momentum. | [d3-force-bounce](https://github.com/vasturiano/d3-force-bounce) | <ul><li>[Newton's cradle](https://observablehq.com/@vasturiano/newtons-cradle)</li><li>[Entropy](https://observablehq.com/@vasturiano/entropy)</li><li>[Brownian motion](https://bl.ocks.org/mikeskaug/27de9c33d44d6b415b2c7b3e7362cde8)</li></ul> |
| [d3.forceBoundary](https://www.npmjs.com/package/d3-force-boundary) | Spring-like force to keep nodes within a rectangular container. | [d3-force-boundary](https://www.npmjs.com/package/d3-force-boundary) | <ul><li>[Force Boundary Demo](https://observablehq.com/@john-guerra/d3-force-boundary)</li><li>[Disjoint Graph](https://observablehq.com/d/186feb840a7e5b06)</li></ul> |
| [d3.forceCenter](https://github.com/d3/d3-force#centering) | Translate all nodes as a group towards the center of the canvas. Manipulates nodes coordinates directly, instead of their velocity. | [d3-force](https://github.com/d3/d3-force#centering) (core) | <ul><li>[Force-directed graph](https://observablehq.com/@d3/force-directed-graph)</li></ul> |
| [d3.forceConstant](https://www.npmjs.com/package/d3-force-constant) | Constant acceleration force. Useful to simulate permanent influences like weight and wind. | [d3-force-constant](https://github.com/vasturiano/d3-force-constant) | <ul><li>[Pendulum](https://bl.ocks.org/vasturiano/17fd83953443cb6b4b76fecac5779797)</li></ul> |
| [d3.forceCluster](https://www.npmjs.com/package/d3-force-cluster) | Spring-like force to attract nodes towards a set of cluster focus points. | [d3-force-cluster](https://github.com/ericsoco/d3-force-cluster) | <ul><li>[Cluster layout](https://bl.ocks.org/ericsoco/4e1b7b628771ae77753842e6dabfcef3)</li><li>[Clustered attraction](https://bl.ocks.org/ericsoco/d2d49d95d2f75552ac64f0125440b35e)</li></ul> |
| [d3.forceCluster-3d](https://www.npmjs.com/package/d3-force-cluster-3d) | Spring-like force to attract nodes towards a set of cluster focus points, working in three dimensions. | [d3-force-cluster-3d](https://github.com/vasturiano/d3-force-cluster-3d) | |
| [d3.forceCollide](https://github.com/d3/d3-force#collision) | Repelling force that prevents circular nodes from overlapping with each other. | [d3-force](https://github.com/d3/d3-force#collision) (core) | <ul><li>[Collision detection](https://observablehq.com/@d3/collision-detection/2)</li><li>[Venn](https://bl.ocks.org/emeeks/6a77dbcf149b4b9e772b30af71d11b06)</li><li>[Hamilton characters](https://bl.ocks.org/sxywu/570df88e66e420191d33dc5b5650aaf4)</li></ul> |
| [d3.forceContainer](https://www.npmjs.com/package/d3-force-container) | Constrain nodes to a bounding box. | [d3-force-container](https://github.com/1wheel/d3-force-container) | <ul><li>[Faces](https://bl.ocks.org/1wheel/68073eeba4d19c454a8c25fcd6e9e68a)</li></ul> |
| [d3.forceGravity](https://www.npmjs.com/package/d3-force-gravity) | Gravity-like (inverse-square distance) force to attract nodes to a particular *<x,y>* point. | [d3-force-gravity](https://github.com/sohamkamani/d3-force-gravity) | <ul><li>[Gravity demo](http://www.sohamkamani.com/d3-force-gravity__demo/)</li></ul> |
| [d3.forceLimit](https://www.npmjs.com/package/d3-force-limit) | Hard limit nodes positions to a specified range, with optionally a cushioning effect. | [d3-force-limit](https://github.com/vasturiano/d3-force-limit) | <ul><li>[Container Boundaries](https://vasturiano.github.io/d3-force-pod/example/basic/)</li><li>[Cushioned Walls](https://observablehq.com/@vasturiano/d3-force-limit)</li></ul> |
| [d3.forceLink](https://github.com/d3/d3-force#links) | Spring-like attraction/repulsion force applied to node-pairs. | [d3-force](https://github.com/d3/d3-force#links) (core) | <ul><li>[Force-directed tree](https://observablehq.com/@d3/force-directed-tree)</li><li>[Lattice](https://observablehq.com/@d3/force-directed-lattice)</li></ul> |
| [d3.forceMagnetic](https://www.npmjs.com/package/d3-force-magnetic) | Inverse-square (distance) attraction/repulsion force applied to all nodes or dedicated node-pair edges. Useful to simulate natural occurring forces such as gravity or electrostatic. | [d3-force-magnetic](https://github.com/vasturiano/d3-force-magnetic) | <ul><li>[Accretion](https://observablehq.com/@vasturiano/accretion)</li><li>[Orbits](https://observablehq.com/@vasturiano/orbital-trajectory)</li></ul> |
| [d3.forceManyBody](https://github.com/d3/d3-force#many-body) | Inverse-linear (distance) attraction/repulsion force applied to all nodes. Typically used as node repulsion in force-directed graphs for a distributed spread. | [d3-force](https://github.com/d3/d3-force#many-body) (core) | <ul><li>[Disjoint graph](https://observablehq.com/@d3/disjoint-force-directed-graph)</li></ul> |
| [d3.forceManyBodyReuse](https://www.npmjs.com/package/d3-force-reuse) | Faster inverse-linear (distance) attraction/repulsion force applied to all nodes. Typically used as node repulsion in force-directed graphs for a distributed spread. Runs faster than d3.forceManyBody by reusing approximations. | [d3-force-reuse](https://github.com/twosixlabs/d3-force-reuse) | <ul><li>[Les Miserables graph](https://bl.ocks.org/rpgove/98820c49a3d7fd0d4d628402536aa60b)</li><li>[Speed comparison](https://bl.ocks.org/rpgove/ecee35052e3e81126dcefff134c06dae)</li></ul> |
| [d3.forceManyBodySampled](https://www.npmjs.com/package/d3-force-sampled) | Linear-time inverse-linear (distance) attraction/repulsion force applied to all nodes. Typically used as node repulsion in force-directed graphs for a distributed spread. Runs faster than d3.forceManyBody and d3.forceManyBodyReuse by using the Random Vertex Sampling algorithm. | [d3-force-sampled](https://github.com/twosixlabs/d3-force-sampled) | <ul><li>[Animated layout](https://bl.ocks.org/rpgove/14bf7407d66cd364ce399ea0540e67b9)</li><li>[Speed comparison with Barnes-Hut](https://bl.ocks.org/rpgove/28345b65a65753ecbabc3acbe30c3d70)</li></ul> |
| [d3.forceRadial](https://github.com/d3/d3-force#forceRadial) | Spring-like force to attract nodes towards the closest point on a circle or sphere surface. | [d3-force](https://github.com/d3/d3-force#forceRadial) (core) | <ul><li>[Radial force](https://bl.ocks.org/mbostock/cd98bf52e9067e26945edd95e8cf6ef9)</li><li>[3D Radial force](https://observablehq.com/@vasturiano/3d-radial-force)</li></ul> |
| [d3.forceSurface](https://www.npmjs.com/package/d3-force-surface) | Elastic collision force between nodes and surfaces, defined as line-segments. | [d3-force-surface](https://github.com/vasturiano/d3-force-surface) | <ul><li>[Pong](https://observablehq.com/@vasturiano/quad-pong)</li><li>[Particle container](https://observablehq.com/@vasturiano/entropy)</li></ul> |
| [d3.forceX](https://github.com/d3/d3-force#forceX) | Horizontal spring-like attraction force. | [d3-force](https://github.com/d3/d3-force#forceX) (core) | <ul><li>[Beeswarm](https://observablehq.com/@d3/beeswarm)</li></ul> |
| [d3.forceY](https://github.com/d3/d3-force#forceY) | Vertical spring-like attraction force. | [d3-force](https://github.com/d3/d3-force#forceY) (core) | <ul><li>[Vertical beeswarm](https://bl.ocks.org/jonsadka/ad1a3698615485a310f9228ed7ea93cd)</li></ul> |
| [d3.forceZ](https://github.com/vasturiano/d3-force-3d#forceZ) | Spring-like attraction force in the Z dimension for 3D representations. | [d3-force-3d](https://github.com/vasturiano/d3-force-3d#forceZ) | - |
| [forceInABox](https://github.com/john-guerra/forceInABox) | Force implementation of the group-in-a-box layout algorithm. | [forceInABox](https://github.com/john-guerra/forceInABox) | <ul><li>[Force in a box](https://observablehq.com/@john-guerra/force-in-a-box)</li></ul> |

## Modules

| Name | Description | Code | Example |
|:---:|---|:---:|---|
| [d3-force-3d](https://www.npmjs.com/package/d3-force-3d) | Extended version of d3-force to run simulations in 3D or 1D. | [d3-force-3d](https://github.com/vasturiano/d3-force-3d) | <ul><li>[Multi-dimensional force simulation](https://observablehq.com/@vasturiano/multi-dimensional-d3-force-simulation)</li></ul> |
| [d3.forceEdgeBundling](https://github.com/upphiminn/d3.ForceBundle) | Force-directed edge bundling algorithm. Self-organise edges on thick mesh graphs to decrease visual clutter. | [d3.forceBundle](https://github.com/upphiminn/d3.ForceBundle) | <ul><li>[US airline routes](http://bl.ocks.org/upphiminn/6515478)</li><li>[FDEB on force-directed graph](https://bl.ocks.org/vasturiano/7c5f24ef7d4237f7eb33f17e59a6976e)</li></ul> |
| [d3-force-pod](https://www.npmjs.com/package/d3-force-pod) | Scaffolding component that automatically draws nodes/links according to a set of forces, for easy prototyping of force simulations. | [d3-force-pod](https://github.com/vasturiano/d3-force-pod) | <ul><li>[Use the Force](https://observablehq.com/@vasturiano/use-the-force)</li><li>[Beeswarm](https://bl.ocks.org/vasturiano/784cbb2a21fa133a41c83768d2e67f0d)</li></ul> |

## Prototype Ideas

| Name | Description | Example |
|:---:|---|---|
| Brownian motion | Random particles hit the nodes and change their speeds. | [Brownian Motion Urquhart](https://bl.ocks.org/Fil/75f14da692354b49a88b9c015324eaae) | 
| K-Means | K-means clusters can be computed as a force that colors nodes. | [K-Means as a force](https://bl.ocks.org/Fil/ef8e0be0147a69bb1d2adc77c66a80b6) |
| tSNE | tSNE computes positions in a webworker, and those positions are used as a force (allowing nodes to converge to their tSNE position while negotiating collisions etc.) | [tSNE applied as a force](https://bl.ocks.org/Fil/33066cb4f74d35a737355f3b7a2c26b1) |

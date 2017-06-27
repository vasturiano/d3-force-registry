# d3-force-registry
A curated compilation of plugins and all-things related to [d3-force](https://github.com/d3/d3-force).

## Force Plugins

| Plugin | Description | Code | Examples |
|:---:|---|:---:|---|
| [d3.bboxCollide](https://www.npmjs.com/package/d3-bboxCollide) | Repelling force that prevents rectangular nodes from overlapping with each other. Great for avoiding label overlaps. | [d3-bboxCollide](https://github.com/emeeks/d3-bboxCollide) | <ul><li>[Guitar hero](https://bl.ocks.org/emeeks/b562c2c449ee30ec577f2d8339b2ce1c)</li><li>[Word clouds](https://bl.ocks.org/emeeks/19a1d77fc6ad812faedb648218b7ad60)</li></ul> |
| [d3.forceAttract](https://www.npmjs.com/package/d3-force-attract) | Spring-like force to attract nodes to a particular *<x,y>* point. | [d3-force-attract](https://github.com/ericsoco/d3-force-attract) | <ul><li>[Mouse following](https://bl.ocks.org/ericsoco/7eebab15da4bb1040977da508aebbff6)</li><li>[Multiple attraction](https://bl.ocks.org/ericsoco/6e0573860e7f6655cee885d8b1b84065)</li></ul> |
| [d3.forceBounce](https://www.npmjs.com/package/d3-force-bounce) | Elastic collision force between nodes. Useful to simulate natural collisions between circular objects that conserve energy and momentum. | [d3-force-bounce](https://github.com/vasturiano/d3-force-bounce) | <ul><li>[Newton's cradle](https://bl.ocks.org/vasturiano/0a05e58d5122cde888793c374d587aac)</li><li>[Entropy](https://bl.ocks.org/vasturiano/2992bcb530bc2d64519c5b25201492fd)</li><li>[Brownian motion](https://bl.ocks.org/mikeskaug/27de9c33d44d6b415b2c7b3e7362cde8)</li></ul> |
| [d3.forceCenter](https://github.com/d3/d3-force#centering) | Translate all nodes as a group towards the center of the canvas. Manipulates nodes coordinates directly, instead of their velocity. | [d3-force](https://github.com/d3/d3-force#centering) (core) | <ul><li>[Force-directed graph](https://bl.ocks.org/mbostock/f584aa36df54c451c94a9d0798caed35)</li></ul> |
| [d3.forceCluster](https://www.npmjs.com/package/d3-force-cluster) | Spring-like force to attract nodes towards a set of cluster focus points. | [d3-force-cluster](https://github.com/ericsoco/d3-force-cluster) | <ul><li>[Cluster layout](https://bl.ocks.org/ericsoco/4e1b7b628771ae77753842e6dabfcef3)</li><li>[Clustered attraction](https://bl.ocks.org/ericsoco/d2d49d95d2f75552ac64f0125440b35e)</li></ul> |
| [d3.forceCollide](https://github.com/d3/d3-force#collision) | Repelling force that prevents circular nodes from overlapping with each other. | [d3-force](https://github.com/d3/d3-force#collision) (core) | <ul><li>[Collision detection](https://bl.ocks.org/mbostock/3231298)</li><li>[Venn](https://bl.ocks.org/emeeks/6a77dbcf149b4b9e772b30af71d11b06)</li><li>[Hamilton characters](https://bl.ocks.org/sxywu/570df88e66e420191d33dc5b5650aaf4)</li></ul> |
| [d3.forceContainer](https://www.npmjs.com/package/d3-force-container) | Constrain nodes to a bounding box. | [d3-force-container](https://github.com/1wheel/d3-force-container) | <ul><li>[Faces](https://bl.ocks.org/1wheel/68073eeba4d19c454a8c25fcd6e9e68a)</li></ul> |
| [d3.forceLink](https://github.com/d3/d3-force#links) | Spring-like attraction/repulsion force applied to node-pairs. | [d3-force](https://github.com/d3/d3-force#links) (core) | <ul><li>[Force-directed tree](https://bl.ocks.org/mbostock/95aa92e2f4e8345aaa55a4a94d41ce37)</li><li>[Cloth](https://bl.ocks.org/mbostock/1b64ec067fcfc51e7471d944f51f1611)</li></ul> |
| [d3.forceMagnetic](https://www.npmjs.com/package/d3-force-magnetic) | Inverse-square (distance) attraction/repulsion force applied to all nodes or dedicated node-pair edges. Useful to simulate natural occurring forces such as gravity or electrostatic. | [d3-force-magnetic](https://github.com/vasturiano/d3-force-magnetic) | <ul><li>[Accretion](https://bl.ocks.org/vasturiano/27fbd16d7e9131fbc8e8e93113f9896c)</li><li>[Orbits](https://bl.ocks.org/vasturiano/5086628299fa6c1bae0094f93d112634)</li></ul> |
| [d3.forceManyBody](https://github.com/d3/d3-force#many-body) | Inverse-linear (distance) attraction/repulsion force applied to all nodes. Typically used as node repulsion in force-directed graphs for a distributed spread. | [d3-force](https://github.com/d3/d3-force#many-body) (core) | <ul><li>[Blocks graph](http://bl.ocks.org/mbostock/afecf1ce04644ad9036ca146d2084895)</li></ul> |
| [d3.forceSurface](https://www.npmjs.com/package/d3-force-surface) | Bounce nodes off one or more line-segments. Surface contact triggers an elastic collision against the surface angle. | [d3-force-surface](https://github.com/vasturiano/d3-force-surface) | <ul><li>[Pong](https://bl.ocks.org/vasturiano/94107e18d438942f92b217809eb3e7ba)</li><li>[Particle container](https://bl.ocks.org/vasturiano/2992bcb530bc2d64519c5b25201492fd)</li></ul> |
| [d3.forceX](https://github.com/d3/d3-force#forceX) | Horizontal spring-like attraction force. | [d3-force](https://github.com/d3/d3-force#forceX) (core) | <ul><li>[Beeswarm](https://bl.ocks.org/mbostock/6526445e2b44303eebf21da3b6627320)</li></ul> |
| [d3.forceY](https://github.com/d3/d3-force#forceY) | Vertical spring-like attraction force. | [d3-force](https://github.com/d3/d3-force#forceY) (core) | <ul><li>[Vertical beeswarm](https://bl.ocks.org/jonsadka/ad1a3698615485a310f9228ed7ea93cd)</li></ul> |
| [d3.forceZ](https://github.com/vasturiano/d3-force-3d#forceZ) | Spring-like attraction force in the Z dimension for 3D representations. | [d3-force-3d](https://github.com/vasturiano/d3-force-3d#forceZ) | - |

## Modules

| Name | Description | Code | Example |
|:---:|---|:---:|---|
| [d3-force-3d](https://www.npmjs.com/package/d3-force-3d) | Extended version of d3-force to run simulations in 3D or 1D. | [d3-force-3d](https://github.com/vasturiano/d3-force-3d) | <ul><li>[Multi-dimensional force simulation](https://bl.ocks.org/vasturiano/f59675656258d3f490e9faa40828c0e7)</li></ul> | 
| [d3.forceEdgeBundling](https://github.com/upphiminn/d3.ForceBundle) | Force-directed edge bundling algorithm. Self-organise edges on thick mesh graphs to decrease visual clutter. | [d3.forceBundle](https://github.com/upphiminn/d3.ForceBundle) | <ul><li>[US airline routes](http://bl.ocks.org/upphiminn/6515478)</li><li>[FDEB on force-directed graph](https://bl.ocks.org/vasturiano/7c5f24ef7d4237f7eb33f17e59a6976e)</li></ul> |

## Experiments & prototypes

| Name | Description | Example |
|:---:|---|---|
| Brownian motion | Random particles hit the nodes and change their speeds. | [Brownian Motion Urquhart](https://bl.ocks.org/Fil/75f14da692354b49a88b9c015324eaae) | 
| K-Means | K-means clusters can be computed as a force that colors nodes. | [K-Means as a force](https://bl.ocks.org/Fil/ef8e0be0147a69bb1d2adc77c66a80b6) |
| tSNE | tSNE computes positions in a webworker, and those positions are used as a force (allowing nodes to converge to their tSNE position while negotiating collisions etc.) | [tSNE applied as a force](https://bl.ocks.org/Fil/33066cb4f74d35a737355f3b7a2c26b1) |


Please get in touch for any additions/corrections to this list. And as always, use the force!

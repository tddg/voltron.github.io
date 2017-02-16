---
layout: default
---
## Overview

The growing disparity in data storage and retrieval needs of modern
applications is driving the proliferation of a wide variety of
Distributed Object-Based Stores (DOBS). However, the complexities in
implementing DOBS and adapting ever-changing storage requirements
present unique opportunities and engineering challenges.

This paper presents Voltron, a modular and compositional development
platform that eases DOBS programming. Voltron is based on the insight
that DOBS shares common distributed management functionalities (e.g.,
replication, consistency, and topology), and thus their development
can be modularized and reused for building other/new stores. Voltron
takes a single-server data store implementation (called datalet), and
seamlessly enable DOBS services atop the datalets by leveraging
pre-built control modules (called controlet). The resulting DOBS can
be easily extended for new types of services. We demonstrate how
Voltron can enable a wide variety of DOBS services with minimal
engineering efforts. Furthermore, we deploy distributed KV stores
developed by Voltron in a local testbed and a public cloud, and show
that the KV stores perform comparable and sometimes better than
state-of-the-art systems---that require significantly higher
programming and design effort---and scale horizontally to a large
number of nodes.



{::options parse_block_html="true" /}
<div class="text-center" style="padding:10px;">
  ![dab study](/images/arch.png){:.image-responsive .center-block width="60%"}
  **Voltron logical (a) and physical (b) architecture.**
</div>

## People

{:.table}
| [Ali Anwar](http://people.cs.vt.edu/~ali/) | [Yue Cheng](http://people.cs.vt.edu/~yuec/) | [Hai Huang](http://researcher.watson.ibm.com/researcher/view.php?person=us-haih) | [Dongyoon Lee](http://people.cs.vt.edu/~dongyoon/) | [Ali R. Butt](http://people.cs.vt.edu/~butta/) |
| ------------- | ------------- | ------------- | ------------- |
|               |               |               |               |

## Contact

#### ali AT vt.edu
#### yuec AT vt.edu

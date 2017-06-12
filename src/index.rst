========================================
The Open SoC Debug Documentation Library
========================================

The Open SoC Debug Project provides a full-stack debug solution.
The documentation provided caters to different audiences, from people interested in a high-level overview, to users of Open SoC Debug, to developers implementing OSD in their projects, or even contributing to OSD itself.

The :doc:`Overview Documents <01_overview/index>` provide a general big-picture introduction to the ideas and concepts of OSD.
They are written for a wide technical and non-technical audience.

The :doc:`Open SoC Debug Specification <02_spec/index>` describes the architecture and components of OSD.
It is written for developers implementing OSD in their own designs, or extending OSD with custom components.

In addition to the specification, the Open SoC Debug Project also produces an extensible reference implementation of the OSD Specification.
This reference implementation, consisting both of hardware IP components and software tools, is also documented here.

The :doc:`User Guides <03_user/index>` describe how to use the tools provided by the OSD reference implementation.
They are written for developers using OSD to debug software.

The :doc:`Implementer Guides <04_implementer/index>` aim at people who want to integrate OSD into their own SoC designs, or want to develop software for an OSD-enabled SoC.

The :doc:`Identifier Registry <05_idregistry/index>` lists all vendor identifiers used by OSD devices and products.

.. toctree::
   :caption: Introduction
   :hidden:

   01_overview/index


.. toctree::
   :maxdepth: 2
   :caption: Specification
   :hidden:

   02_spec/index
   
   
.. toctree::
   :maxdepth: 2
   :caption: User Guides
   :hidden:

   03_user/index
   
   
.. toctree::
   :maxdepth: 2
   :caption: Implementer Documentation
   :hidden:

   04_implementer/index
   
   
.. toctree::
   :maxdepth: 2
   :caption: Appendix
   :hidden:

   05_idregistry/index
   license
   
   
## pODM (portable OpenDroneMap)

### Overview

This project proposes to extend current OpenDroneMap (ODM) technologies to optimise its use in humanitarian contexts, specifically to enable its use on-the-ground for rapid post-disaster assessment from locally captured aerial imagery. ODM faces two challenges in this context: (1) the ability to split large data-sets for processing across a cluster of multiple computers, and (2) operate across a micro-cluster of devices, potentially in an ‘offline’ environment.

Work completed in 2017 improved ODM’s use on massive datasets through funding from the Humanitarian Innovation Fund (HIF). The extensions added the capacity to split, process independently, and merge larger datasets, while retaining a single matched coordinate system between portions of the project. There remains an important gap relevant to rapid post-disaster assessment: an orchestration component to coordinate the processing of split datasets; that orchestration component will need to be flexible enough and platform independent enough to support both cloud deployed and field deployed clusters of machines. Administration tools for quality control of the orchestration will also need to be built.

### Project Aim

Provision ODM as an end-to-end solution for capture and processing of localised aerial imagery in post-disaster environments.

**Objectives:**
- Provision support for large flights (2,000+ image scenes), by splitting into multiple ODM tasks for parallel processing
- Post-flight metadata generation to assist with splitting
- Design network hardware configuration to support local clusters of ODM processing nodes suitable for deployment in post disaster environments
- Extend ODM to enable orchestration of distributed processing of ODM tasks across local area network of ODM nodes


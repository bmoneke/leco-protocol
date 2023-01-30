# Glossary
An alphabetical list of terms with a short description.
To help distinguish between the plain English meaning of these terms, and our more specific use, we Capitalize terms from this glossary when we refer to the LECO-specific meaning.

:::{glossary}

Actor
    An Actor offers a standardized interface to the LECO network to communicate with some Device. This happens via a Driver contained in the Actor, see {ref}`components.md#actor`. An Actor implements the mapping/translation between LECO messages and the Driver's interface.

Component
    A type of entity, a set of which make up the LECO communication Network, see {ref}`components.md#components`.

Coordinator
    A Component primarily concerned with routing/coordinating the message flow, see {ref}`components.md#coordinator`.

Device
    Some piece of hardware controlled by a Driver.

Director
    A Component which takes part in orchestrating a (i.e. LECO-controlled) measurement setup, see {ref}`components.md#director`.

Driver
    An object that takes care of communicating with a Device. This object is external to LECO, for example coming from and instrument control library like `pymeasure`, `instrumentkit` or `yaq`. See {ref}`components.md#driver`.

LECO
    The **L**aboratory **E**xperiment **CO**ontrol protocol framework.

Network
    The web of Components communicating with each other in an LECO deployment.

Observer
    A Component that receives data from other Components, e.g. for logging, storage, or plotting, see {ref}`components.md#observer`.

Processor
    A Component on the LECO network which runs some kind of processing operation on one or more inputs and produces one or more outputs. Can be stateful or stateless. See {ref}`components.md#processor`.

:::
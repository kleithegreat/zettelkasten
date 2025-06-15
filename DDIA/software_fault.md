# Software Fault
A *software fault* is a specific type of [[fault]] that occurs when a piece of software does not behave as expected or deviates from its intended functionality.

As opposed to hardware faults, which tend to be more random and independent, software faults tend to be more systematic. For example:
- A software bug that causes every instance of a service to crash under certain conditions
- Runaway processes that consume all available memory
- One service crashing and taking down dependent services

The bugs that cause software faults are usually rare and reveal certain assumptions about the system that are not always true in practice.

There is no single solution to software faults, but common strategies include:
- Carefully thinking about assumptions and architecture of the system
- Testing thoroughly
- Process isolation
- Monitoring and alerting to detect issues early
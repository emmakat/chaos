# chaos resources
chaos resources

https://github.com/dastergon/awesome-chaos-engineering
https://coggle.it/diagram/WiKceGDAwgABrmyv/t/chaos-engineering-companies%2C-people%2C-tools-practices/0a2d4968c94723e48e1256e67df51d0f4217027143924b23517832f53c536e62
https://www.gremlin.com/community/tutorials/chaos-engineering-the-history-principles-and-practice/
https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-controlled-chaos
https://principlesofchaos.org/
https://github.com/chaostoolkit-incubator/chaostoolkit-azure

Chaos Engineering can be thought of as the facilitation of experiments to uncover systemic weaknesses.  These experiments follow four steps:
Start by defining ‘steady state’ as some measurable output of a system that indicates normal behavior.
Hypothesize that this steady state will continue in both the control group and the experimental group.
Introduce variables that reflect real world events like servers that crash, hard drives that malfunction, network connections that are severed, etc.
Try to disprove the hypothesis by looking for a difference in steady state between the control group and the experimental group.
The harder it is to disrupt the steady state, the more confidence we have in the behavior of the system.  If a weakness is uncovered, we now have a target for improvement before that behavior manifests in the system at large.

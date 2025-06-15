# Reliability
*Reliability* is one of the three concerns of distributed [[data-intensive|systems]]. We want our systems to be correct at the right level of performance despite potential [[fault|faults]].

Faults cannot be completely eliminated, so it is usually best to design systems to prevent faults from causing [[failure|failures]].

We generally prefer fault-tolerance rather than fault prevention, but there are still cases where prevention is better than cure.

The importance of reliability depends on your use case. For example, a system that is used for financial transactions must be more reliable than one that is used for a social media application.

Sacrificing reliability for development cost or operational cost can be appropriate in some cases, but we must be concsious of what we are sacrificing.
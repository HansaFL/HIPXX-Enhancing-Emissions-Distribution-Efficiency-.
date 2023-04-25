# HIP: Enhancing Emissions Distribution Efficiency

Summary: This HIP proposes to remove redundancy from the DAO score calculation, which has become unnecessary following the implementation of HIP 19's device restrictions. Specifically, the A score of the DAO score, as defined in HIP 51, will be updated from its current formula, (Number of active devices x onboarding fee)^.25, to a simplified version, (Number of active devices)^.25.

Current formula:
A=(Number of active devices×onboarding fee)0.25A=(Number of active devices×onboarding fee)0.25

Proposed formula:
A=(Number of active devices)0.25A=(Number of active devices)0.25


## Background ##
HIP 51 introduced the DAO score, which is used to determine the share of emissions each subDAO receives based on three performance metrics. One of these metrics is known as the A score. The A score gives credit to the number of devices that are active on a particular subDAO network, while also taking into account the onboarding fee. This fee was enacted to reduce the potential for exploits and discourage malicious actors from creating a zombie network. However, with the implementation of HIP 19, the Helium network has established additional protections that make the inclusion of the onboarding fee in the A score calculation unnecessary.

## Stakeholders ##

The proposed changes to the A score calculation in the DAO score will impact various stakeholders within the Helium ecosystem. These stakeholders include:

1. **SubDAO Members:** SubDAO members will be directly impacted by the changes in the A score calculation, as it will determine the share of emissions they receive. The proposed update aims to create a more equitable distribution, taking into account the increased protections provided by HIP 19.

2. **Device Owners and Users:** Device owners and users who have joined a subDAO network will experience a potential change in the distribution of emissions. The removal of the onboarding fee from the A score calculation may encourage more device owners to participate in subDAO networks.

3. **SubDAO veHNT Delegators:** As veHNT delegators have a vested interest in the performance and growth of their respective subDAOs, they will also be impacted by the changes in the A score calculation. The proposed update may influence their decisions on which subDAOs to support, as the distribution of emissions may shift based on the revised A score calculation.


## Drawbacks ##

While the proposed changes to the A score calculation aim to improve the distribution of emissions in the Helium ecosystem, there are potential drawbacks to consider:

1. **Potential Exploitation:** Although HIP 19 provides additional protections against exploitation, removing the onboarding fee from the A score calculation may still leave some room for malicious actors to attempt to game the system. It's essential to closely monitor for any unintended consequences or emerging threats.

2. **Adjustment Period:** Changing the A score calculation may require an adjustment period for the Helium community, subDAO members, device owners, and veHNT delegators as they adapt to the new distribution of emissions. This could cause temporary disruptions or confusion.

3. **Impact on Existing SubDAOs:** Existing subDAOs that have been operating with the current A score calculation may be negatively affected by the proposed changes. The redistribution of emissions could lead to disagreements or dissatisfaction among some stakeholders, particularly if they perceive the changes as unfavorable to their interests.

## Rationale and Alternatives

The main rationale behind this proposal is to simplify the A score calculation while taking advantage of the additional protections provided by HIP 19. This aims to streamline the emissions distribution process and reduce potential redundancy in the DAO score. 

The key reasons for this proposal are:

1. **Reduced Redundancy:** With the introduction of HIP 19, the onboarding fee component in the A score calculation has become less relevant, as the additional protections in HIP 19 have diminished the risk of exploitation.

2. **Simplified Calculation:** By removing the onboarding fee from the A score calculation, the process becomes more straightforward and easier to understand for stakeholders.

3. **Better Emissions Distribution:** The proposed changes aim to provide a more accurate representation of subDAOs' contributions to the Helium ecosystem, allowing for a fairer distribution of emissions.

Alternatives that could be considered include:

1. **Maintaining the Current Calculation:** One alternative would be to keep the current A score calculation, with the onboarding fee included. However, this might lead to unnecessary complexity and redundancy, given the added protections from HIP 19.

2. **Adjusting the A Score Calculation Differently:** Another option is to explore different adjustments to the A score calculation that might achieve similar goals while addressing the potential drawbacks of this proposal. This could include introducing new parameters or modifying the existing calculation in other ways.

3. **Introducing Additional Protections:** Instead of changing the A score calculation, more protective measures could be introduced to further reduce the risk of exploitation while maintaining the current calculation. This approach would require a thorough evaluation of potential vulnerabilities and the development of new mechanisms to address them.


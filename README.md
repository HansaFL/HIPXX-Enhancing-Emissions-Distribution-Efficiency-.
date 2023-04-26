# HIP: Enhancing HNT Emissions Distribution 
<i> This HIP is intended to be voted on by stakers using veHNT </i>

Summary: This HNT DAO HIP proposes to remove redundancy from the DAO score calculation, which has become unnecessary following the implementation of HIP 19's device restrictions. Specifically, the A score of the DAO score, as defined in HIP 51, will be updated to a more efficient equation.

Current formula:

![Current HIP 51 Formula](https://github.com/HansaFL/HIPXX-Enhancing-Emissions-Distribution-Efficiency-./blob/a59a22a922ffb6da9ed3457a923f930ef0baf0c5/png3.PNG)

Proposed formula:

![Future HIP 51 Formula](https://github.com/HansaFL/HIPXX-Enhancing-Emissions-Distribution-Efficiency-./blob/a59a22a922ffb6da9ed3457a923f930ef0baf0c5/png2.PNG)


## Background ##
HIP 19 introduced a set of device restrictions that help mitigate the risks associated with malicious behavior in the network. These restrictions require devices to adhere to specific guidelines, such as approved hardware, firmware, and network settings. As a result, the likelihood of someone creating a malicious or zombie network is significantly reduced. Consequently, the onboarding fee, which was originally intended to deter such behavior, has become less relevant in the A score calculation, making it unnecessary to include it in the equation.

## Stakeholders ##

The proposed changes to the A score calculation in the DAO score will impact various stakeholders within the Helium ecosystem. These stakeholders include:

1. **veHNT Delegators**: Delegators receive HNT emissions and will be directly impacted by the changes in the A score calculation, as it will determine the share of HNT emissions they receive. The proposed update aims to create a more equitable distribution, taking into account the increased protections provided by HIP 19.
2. **Device Owners and Users**: Device owners and users who have joined a subDAO network will experience a potential change in the distribution of HNT emissions. The removal of the onboarding fee from the A score calculation may encourage more device owners to participate in subDAO networks.
3. **veHNT Stakers**: As veHNT stakers have a vested interest in the performance and growth of their respective subDAOs, they will also be impacted by the changes in the A score calculation. The proposed update may influence their decisions on which subDAOs to support, as the distribution of HNT emissions may shift based on the revised A score calculation.

## Drawbacks ##

While the proposed changes to the A score calculation aim to improve the distribution of HNT emissions in the Helium ecosystem, there are potential drawbacks to consider:

1. **Potential Exploitation**: Although HIP 19 provides additional protections against exploitation, removing the onboarding fee from the A score calculation may still leave some room for malicious actors to attempt to game the system. It's essential to closely monitor for any unintended consequences or emerging threats.

2. **Adjustment Period**: Changing the A score calculation may require an adjustment period for the Helium community, subDAO members, device owners, and veHNT delegators as they adapt to the new distribution of HNT emissions. This could cause temporary disruptions or confusion.

3. **Impact on Existing SubDAOs**: Existing subDAOs that have been operating with the current A score calculation may be negatively affected by the proposed changes. The redistribution of HNT emissions could lead to disagreements or dissatisfaction among some stakeholders, particularly if they perceive the changes as unfavorable to their interests.

## Rationale and Alternatives

The main rationale behind this proposal is to simplify the A score calculation while taking advantage of the additional protections provided by HIP 19. This aims to streamline the HNT emissions distribution process and reduce potential redundancy in the DAO score. 

**The key reasons for this proposal are:**

1. **Reduced Redundancy**: With the introduction of HIP 19, the onboarding fee component in the A score calculation has become less relevant, as the additional protections in HIP 19, such as stricter device restrictions, have diminished the risk of exploitation.

2. **Simplified Calculation**: By removing the onboarding fee from the A score calculation, the process becomes more straightforward and easier to understand for stakeholders.

3. **Better HNT Emissions Distribution**: The proposed changes aim to provide a more accurate representation of subDAOs' contributions to the Helium ecosystem, allowing for a fairer distribution of HNT emissions.

**Alternatives that could be considered:**

1. **Maintaining the Current Calculation:** One alternative would be to keep the current A score calculation, with the onboarding fee included. However, doing so might lead to unnecessary complexity, as managing the onboarding fee using on-chain mechanisms like NFTs and storing the associated data would require additional resources and potentially increase costs. Given the added protections from HIP 19, these complexities and associated expenses could be avoided by removing the onboarding fee from the A score calculation.

2. **Adjusting the A Score Calculation Differently**: Another option is to explore different adjustments to the A score calculation that might achieve similar goals while addressing the potential drawbacks of this proposal. This could include introducing new parameters or modifying the existing calculation in other ways.
3. **Introducing Additional Protections**: Instead of changing the A score calculation, more protective measures could be introduced to further reduce the risk of exploitation while maintaining the current calculation. This approach would require a thorough evaluation of potential vulnerabilities and the development of new mechanisms to address them.


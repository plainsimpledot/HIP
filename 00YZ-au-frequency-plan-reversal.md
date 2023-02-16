# HIP YZ: Australian Frequency Plan Reversal - AU915

- Author(s): [@plainsimpledot](https://github.com/plainsimpledot)
  [@Buckshot22](https://github.com/Buckshot22), [@mcauser](https://github.com/mcauser),
  [@leogaggl](https://github.com/leogaggl), [@tonysmith55](https://github.com/tonysmith55)
- Start Date: 2023-02-16
- Category: Technical
- Original HIP PR:
- Tracking Issue:
- Status: Daft

## Summary

This Helium Improvement Proposal is designed to allow the investors in the Helium network in
Australia to have a voice in determining the best frequency plan for the country, as was promised by
the Helium Foundation in early 2022.

## Motivation

On 17 November 2022, the Helium Foundation made the decision to move Australia to a hybrid
AS923/AU915 frequency. This decision was made without any HIP or due process and in conflict with
promises made previously in regard to the frequency plan.

The excuse given related to a footnote inserted in a LORA Alliance document by an industry player
which the Alliance themselves have confirmed in no way reflects the LORA Alliance official stance.
The LORA Alliance also confirmed that intentions to diminish the AU915 frequency plan which were
hinted at by the Helium Foundation are completely false and there are no such plans.

We believe, backed up by expert opinions including senior members of the LORA Alliance, that the
only effective way to support AS923 is to utilise 16 channel gateways or allow investor/operators in
densely populated areas to voluntarily operate on AS923.

AU915 is better suited to the Australian environment and use cases and will allow for roaming on TTN
and ThingsIX networks. These are likely to bring greater benefits than a single commercial operator
who has limited use cases and provides their own coverage in areas they are utilising sensors. This
also allows gateway operators who will move over to ThingsIX to dual purpose their gateways rather
than to lose them from the Helium network completely.

## Stakeholders

Australia has a vibrant communtiy of members dedicated to furthering LORAWAN in this region. We have
several channels of communication avaialable, including the official Helium discord and the LoRawan
Australia discords. The community also run numerous facebook groups for all of the major regions in
Australia.

Voting will be 1 vote per hotspot asserted in the Australian continent. 

## Detailed Explanation

The change is extremely simple in that it is reverting to a known working configuration utilising a 
LORA Alliance approved frequency plan at 27 dBm which is within the permitted range for Australia.

The code limiting votes to a per hotspot asserted to the Australian continent is outlined below.

## Drawbacks

- Why should we _not_ do this?
- What problems could occur if we do this?

## Rationale and Alternatives

This is your chance to discuss your proposal in the context of the whole design space. This is
probably the most important section!

- Why is this design the best in the space of possible designs?
- What other designs have been considered and what is the rationale for not choosing them?
- What is the impact of not doing this?

## Unresolved Questions

- What parts of the design do you expect to resolve through the HIP process before this gets merged?
- What parts of the design do you expect to resolve through the implementation of this feature?
- What related issues do you consider out of scope for this HIP that could be addressed in the
  future independently of the solution that comes out of this HIP?
- Are there dependencies, milestones, or dates that need to be met for this HIP to succeed?

## Deployment Impact

Describe how this design will be deployed and any potential impact it may have on current users of
this project.

- How will current users be impacted?
- How will existing documentation/knowledge base need to be supported? Any content to change at
  <http://docs.helium.com>?
- Is this backwards compatible? Can this HIP be undone?
  - If not, what is the procedure to migrate?

## Success Metrics

What metrics can be used to measure the success of this design? Are any new ETL reports needed to
measure the success?

- What should we measure to prove a performance increase?
- What should we measure to prove an improvement in stability?
- What should we measure to prove a reduction in complexity?
- What should we measure to prove an acceptance of this by its users?

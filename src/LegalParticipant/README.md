# Information for LegalParticipant

## Files
- The LegalParticipant-instance_20.10-conform.json is a version that is **not accepted** by the Compliance Service but relates to the LegalParticipantShape.
- The LegalParticipant-instance_compliance-service-conform.json is a version that is **accepted** by the Compliance Service but does not relate to the LegalParticipantShape.

The reason for this is currently not clear and has to be analysed.

## Prepared Participant credentials 
There are already prepared participant credentials that can be used by project partners. There are credentials for:
- LegalParticipant (based on LegalParticipant-instance_compliance-service-conform.json)
- LegalRegistrationNumber
- TermsAndConditions

All three credentials must be sent to the Compliance Service along with the other credentials encapsulating the claims to get a positive response.

The prepared credentials are located here:
- https://participant.gxfs.gx4fm.org/{projectPartner}/legalParticipant.json
- https://participant.gxfs.gx4fm.org/{projectPartner}/legalRegistration.json
- https://participant.gxfs.gx4fm.org/{projectPartner}/termsAndConditions.json


where `{projectPartner}` is the one of the names of the project partner in following list:
- 3dmapping
- ascs
- bmw
- continental
- dlr
- gx4fm-plcaad
- infineon
- ivi.fraunhofer
- msg-systems-ag
- setlabs
- tracetronic
- triangraphics
- tu-berlin
- tu-muenchen

These credentials can be reused by the project partners.

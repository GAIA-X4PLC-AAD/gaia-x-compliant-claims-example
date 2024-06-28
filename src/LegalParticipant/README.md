# Information for LegalParticipant

## General
The LegalParticipant-instance.json an example how claims can look like for a LegalParticipant.

> Note: As a provider of meta-data it is not required to create an instance of the LegalParticipant for every offering since the LegalParticipant needs to be onboarded in the Federated Catalogue. 
> What the data provider needs are the three participant credentials (`LegalParticipant`, `LegalRegistrationNumber`, `TermsAndConditions`) that are sent to the Compliance Service along with the other credentials (see below). The ID of the LegalParticipant is then referenced in the other credentials.

> Note: This is an example that is **accepted** by the Compliance Service. But it does not relate to the LegalParticipantShape.

## Prepared Participant credentials 
There are already prepared participant credentials that can be used by project partners. There are credentials for:
- `LegalParticipant` (based on `LegalParticipant-instance.json`)
- `LegalRegistrationNumber`
- `TermsAndConditions`

All three credentials must be sent to the Compliance Service along with the other credentials encapsulating the claims to get a positive response.

The prepared credentials are located here:
- https://participant.gxfs.gx4fm.org/{projectPartner}/legalParticipant.json
- https://participant.gxfs.gx4fm.org/{projectPartner}/legalRegistration.json
- https://participant.gxfs.gx4fm.org/{projectPartner}/termsAndConditions.json

In addition to that there is also a prepared did for each project partner here:
- https://participant.gxfs.gx4fm.org/{projectPartner}/did.json


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

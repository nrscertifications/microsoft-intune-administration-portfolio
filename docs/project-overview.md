# Project Overview

This portfolio documents practical endpoint-administration work across Microsoft Intune, Microsoft Entra ID, Windows 11, Windows Server Active Directory, and Group Policy in non-production environments.

## Portfolio Structure

- The main README provides the workstream overview, demonstrated skills, and selected evidence.
- Workstream documents explain related administration in numbered technical phases.
- The screenshot archive retains unique lab configuration, verification, intermediate, and troubleshooting frames.
- The [evidence index](evidence-index.md) provides descriptions and links for every published lab screenshot.

## Verified Environment

| Component | Values visible in the evidence | Relevant work |
|---|---|---|
| Earlier Microsoft Entra tenant | `nrsintunelabs.onmicrosoft.com` | Windows account registration and Company Portal account selection |
| Current Intune / Microsoft Entra tenant | `narindersharmalabsxyz.onmicrosoft.com` | Dynamic group, enrollment settings, Managed Google Play, restriction, and policy-set workflows |
| Custom domain | `narindersharmalabs.xyz` | Successful Windows enrollment CNAME validation |
| Active Directory domain | `narindersharmalabs.xyz`, NetBIOS `NSLABS` | Domain-connected Windows client and Group Policy administration |
| Domain controller | `MDM-Server`, Windows Server 2016 Datacenter Evaluation | Group Policy Management and Central Store update |
| Registration client | `TheResilientOne`, Windows version `10.0.26200.9168` | Registered device record with MDM None |
| Windows provisioning project | `AutoenrollmentProvisioning`, Windows Configuration Designer | Bulk-token retrieval and protected package creation |

The current AD domain is `narindersharmalabs.xyz`; the `ad.narindersharmalabs.xyz` forest from the separate Microsoft 365 portfolio is not assumed to be part of this batch. The token-issuing tenant for the provisioning project is not visible in the supplied screenshots.

## Verified Outcomes

| Area | Outcome documented |
|---|---|
| Device identity | Work account added and registered device record reviewed |
| Device grouping | Dynamic security group created with Windows build-prefix criteria |
| Enrollment readiness | CNAME validation succeeded and Managed Google Play was connected |
| Enrollment restrictions | Three-device restriction created; assignment persistence remains to be checked |
| Group Policy troubleshooting | Updated Central Store restored the missing automatic-enrollment setting |
| Group Policy preparation | Enabled and User Credential selected; domain-level GPO link visible |
| Provisioning | Protected package built and generated files reviewed |
| Policy sets | Container created and Assigned status verified; payload selectors reviewed without deployment objects |

## Documentation Standard

The writing describes actual configuration, review, verification, and outcomes. Selected screenshots support the surrounding phase rather than every navigation click. Microsoft Entra registration, Active Directory domain membership, MDM enrollment, and policy delivery are treated as distinct states.

Lab names and useful settings remain visible. Personal email addresses and access-enabling values are excluded from public evidence, as described in the [screenshot publishing notes](screenshot-publishing-notes.md).

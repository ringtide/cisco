# RingTide Cisco Provisioning Files
Cisco Provisioning Files are configuration templates and XML definitions used by RingTide and its associated systems for the purpose of automatically provisioning Cisco IP telephones. These files define the phone’s identity, SIP or SCCP registration details, firmware sources, and network parameters. The files are designed to work specifically within the RingTide or Coastal Networks telephony environments.

Access to these files is strictly limited to authorized system administrators and devices enrolled under approved provisioning scopes. Unauthorized modification, redistribution, or use of these files outside of their intended system is prohibited. Each configuration may contain internal reference URLs, extension assignments, and device-specific credentials that must remain confidential. Sharing or exposing these parameters to public sources or third-party servers is considered a security violation.

RingTide does not provide public or customer-facing support for Cisco provisioning templates or the base XML structure contained within this repository. Files are provided solely for automated use within managed deployments. No direct assistance, troubleshooting, or setup guidance will be offered for independent or third-party integrations.

The files within this repository are designed for compatibility with FreePBX, CUCM, and SCCPManager environments. Custom parameters, such as TFTP addresses or device-specific model profiles, may differ between deployments and should not be altered without proper authorization. Users attempting to repurpose these configurations for unrelated systems do so at their own risk.

Do not use these files for unrelated Cisco environments or third-party hosting platforms. Any attempt to rehost, modify, or apply these configurations to devices not under the administrative control of RingTide may result in service disruption or device lockout. The configuration templates are considered part of internal system operations and should remain untouched unless directed otherwise by a qualified system administrator.

These files are not licensed, sold, or distributed commercially. They are strictly internal provisioning assets intended for controlled use only. By accessing or using any configuration in this repository, you acknowledge that RingTide and its affiliates are not responsible for system errors, failed provisioning attempts, or device behavior resulting from modification or misconfiguration of these files.

For official device provisioning, TFTP servers, and update policies, please refer only to the configurations deployed within approved RingTide systems. Do not upload, mirror, or reuse these files outside of their designated purpose.

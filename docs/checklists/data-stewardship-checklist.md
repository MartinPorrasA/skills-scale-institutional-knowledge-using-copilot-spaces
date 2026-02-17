# Data Stewardship Checklist

## Purpose
This checklist ensures data quality, security, compliance, and governance throughout the project lifecycle. It should be used by Data Stewards to systematically validate data management practices.

---

## Data Planning Phase

### Data Requirements

- [ ] Data needs identified and documented
- [ ] Data sources identified (internal, external, third-party)
- [ ] Data volume and velocity requirements defined
- [ ] Data retention requirements documented
- [ ] Data archival and disposal policies defined
- [ ] Master data entities identified
- [ ] Data relationships and dependencies mapped

### Data Governance

- [ ] Data ownership assigned for each data domain
- [ ] Data classification levels defined (public, internal, confidential, restricted)
- [ ] Data governance policies reviewed and applicable policies identified
- [ ] Compliance requirements identified (GDPR, HIPAA, SOX, etc.)
- [ ] Data privacy requirements documented
- [ ] Data audit requirements defined

---

## Data Design Phase

### Data Architecture

- [ ] Conceptual data model created
- [ ] Logical data model documented
- [ ] Physical data model designed
- [ ] Data dictionary created with metadata
- [ ] Data lineage documented (source to destination)
- [ ] Data integration points identified
- [ ] Data transformation rules documented
- [ ] Master data management strategy defined

### Data Quality Standards

- [ ] Data quality dimensions defined (accuracy, completeness, consistency, timeliness, validity)
- [ ] Acceptable data quality thresholds established
- [ ] Data validation rules defined
- [ ] Data quality metrics identified
- [ ] Data quality monitoring approach defined
- [ ] Data cleansing procedures documented

### Data Security Design

- [ ] Data access control model defined (RBAC, ABAC)
- [ ] Encryption requirements identified (at rest, in transit)
- [ ] Data masking/anonymization requirements defined
- [ ] Sensitive data identified and tagged
- [ ] Data security controls documented
- [ ] Data breach response plan created

---

## Data Development Phase

### Data Implementation

- [ ] Database schemas created and reviewed
- [ ] Data validation rules implemented
- [ ] Data quality checks automated
- [ ] Data transformation logic implemented
- [ ] Data access controls implemented
- [ ] Data encryption implemented
- [ ] Data masking implemented for non-production environments
- [ ] Data migration scripts developed (if applicable)

### Data Testing

- [ ] Data quality test cases created
- [ ] Data validation test cases created
- [ ] Data integration test cases created
- [ ] Data security test cases created
- [ ] Test data created following data classification rules
- [ ] Data test results documented

---

## Data Migration (If Applicable)

### Pre-Migration

- [ ] Source data profiled and quality assessed
- [ ] Data mapping from source to target completed
- [ ] Data transformation rules validated
- [ ] Data migration plan documented
- [ ] Data validation approach defined
- [ ] Rollback plan created
- [ ] Migration environment prepared

### Migration Execution

- [ ] Data backup completed before migration
- [ ] Data extracted from source system
- [ ] Data transformed according to rules
- [ ] Data quality checks passed
- [ ] Data loaded to target system
- [ ] Data validation performed (record counts, checksums, sample verification)
- [ ] Reconciliation report generated and reviewed
- [ ] Data migration sign-off obtained

### Post-Migration

- [ ] Source and target data reconciled
- [ ] Data quality metrics validated
- [ ] Data lineage updated
- [ ] Data migration report completed
- [ ] Lessons learned documented

---

## Data Operations Phase

### Data Quality Monitoring

- [ ] Data quality dashboards configured
- [ ] Data quality metrics being tracked
- [ ] Data quality alerts configured
- [ ] Data quality reports scheduled
- [ ] Data quality issues triaged and tracked
- [ ] Data quality trends analyzed monthly

### Data Access Management

- [ ] User access provisioned based on approved requests
- [ ] User access reviews scheduled and completed quarterly
- [ ] Privileged access monitored
- [ ] Access audit logs reviewed regularly
- [ ] Terminated user access revoked promptly
- [ ] Data access violations tracked and investigated

### Data Security & Compliance

- [ ] Data encryption validated (at rest and in transit)
- [ ] Sensitive data access logged and monitored
- [ ] Data security scans performed regularly
- [ ] Compliance audits passed
- [ ] Data privacy requests processed (access, deletion, portability)
- [ ] Data breach procedures tested annually
- [ ] Security incidents documented and resolved

### Data Maintenance

- [ ] Data archival jobs running on schedule
- [ ] Data backups completed and validated
- [ ] Data recovery procedures tested
- [ ] Data storage capacity monitored
- [ ] Data performance optimizations applied as needed
- [ ] Obsolete data identified and purged per policy

---

## Data Quality Audit

### Audit Preparation

- [ ] Audit scope and objectives defined
- [ ] Audit schedule established
- [ ] Audit team identified
- [ ] Audit criteria documented
- [ ] Audit tools and scripts prepared
- [ ] Stakeholders notified of audit

### Audit Execution

- [ ] Data completeness verified
  - [ ] All required fields populated
  - [ ] No missing critical data
  - [ ] Record counts match expectations
  
- [ ] Data accuracy validated
  - [ ] Sample data manually verified against source
  - [ ] Calculation logic validated
  - [ ] Reference data verified
  
- [ ] Data consistency checked
  - [ ] Cross-system data reconciled
  - [ ] Data formats standardized
  - [ ] Referential integrity validated
  
- [ ] Data timeliness assessed
  - [ ] Data refresh frequency meets requirements
  - [ ] Data latency within acceptable limits
  - [ ] Stale data identified and addressed
  
- [ ] Data validity confirmed
  - [ ] Data conforms to business rules
  - [ ] Data within acceptable ranges
  - [ ] Invalid data identified and corrected

### Audit Reporting

- [ ] Data quality findings documented
- [ ] Data quality scores calculated
- [ ] Root causes of quality issues identified
- [ ] Remediation actions recommended
- [ ] Audit report reviewed with stakeholders
- [ ] Remediation plan approved and scheduled

---

## Compliance Checklist

### GDPR (If Applicable)

- [ ] Legal basis for data processing documented
- [ ] Data processing activities registered
- [ ] Data subject rights supported (access, rectification, erasure, portability)
- [ ] Consent mechanisms implemented (if consent-based)
- [ ] Privacy notices provided to data subjects
- [ ] Data protection impact assessment (DPIA) completed for high-risk processing
- [ ] Data breach notification procedures in place

### Data Retention

- [ ] Data retention periods defined per data type
- [ ] Retention policy communicated to stakeholders
- [ ] Automated retention enforcement configured
- [ ] Legal hold process documented
- [ ] Destruction/deletion procedures defined and tested

### Audit Trail

- [ ] All data access logged with user ID, timestamp, action
- [ ] All data modifications logged
- [ ] Audit logs protected from tampering
- [ ] Audit logs retained per policy
- [ ] Audit log review process established

---

## Data Steward Responsibilities Summary

**Daily:**
- Monitor data quality alerts
- Review data access logs for anomalies
- Respond to data access requests

**Weekly:**
- Review data quality metrics
- Triage data quality issues
- Meet with Project Manager on data status

**Monthly:**
- Analyze data quality trends
- Conduct user access reviews
- Generate data stewardship report

**Quarterly:**
- Complete data quality audit
- Review and update data governance policies
- Conduct data steward training for team

---

## Escalation Process

**Data Quality Issues:**
- **Low impact:** Log and fix in normal course
- **Medium impact:** Escalate to Project Manager within 24 hours
- **High impact:** Escalate to Project Manager and Sponsor immediately

**Data Security Issues:**
- **Potential breach:** Escalate to Security Team and Sponsor immediately
- **Access violations:** Investigate and report to Project Manager within 4 hours
- **Compliance concerns:** Escalate to Compliance Officer and Sponsor

**Data Availability Issues:**
- **Partial outage:** Escalate to Technical Lead and Project Manager within 1 hour
- **Complete outage:** Escalate to Technical Lead, Project Manager, and Sponsor immediately

---

**Data Steward Signature:** _____________________ **Date:** __________

**Project Manager Signature:** _____________________ **Date:** __________

---

## Related Documents

- [OctoAcme Roles and Personas](../octoacme-roles-and-personas.md)
- [Quality Gates Checklist](quality-gates-checklist.md)
- [Project Execution & Tracking](../octoacme-execution-and-tracking.md)

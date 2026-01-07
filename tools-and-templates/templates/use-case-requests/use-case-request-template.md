# 📋 Use Case Request Template

> **Instructions**: Complete all sections below. Remove this instruction block and any guidance comments (marked with `<!-- -->`) before submitting.

## 📊 Request Information

| **Field** | **Details** |
|-----------|-------------|
| **Request ID** | `UC-YYYY-MM-DD-XXX` <!-- Generate unique identifier --> |
| **Date Submitted** | `YYYY-MM-DD` |
| **Submitted By** | `[Name, Title, Department]` |
| **Priority Level** | `[ ] Critical [ ] High [ ] Medium [ ] Low` |
| **Expected Timeline** | `[Timeframe for implementation]` |

---

## 🎯 Business Context

### 📈 Business Drivers
<!-- Check all that apply and provide details -->

**Primary Driver:**
- [ ] **Risk Mitigation** - Describe the specific risk being addressed
- [ ] **Threat Response** - Identify the threat actors or attack vectors
- [ ] **Compliance Requirement** - Specify regulation/standard (PCI-DSS, SOX, GDPR, etc.)

**Business Justification:**
```
[Explain why this use case is needed from a business perspective]
[Include potential impact if not implemented]
[Reference any recent incidents or threat intelligence]
```

### 🏢 Organizational Impact

**Affected Business Units:**
- [ ] IT Operations
- [ ] Finance
- [ ] HR
- [ ] Legal/Compliance
- [ ] Operations
- [ ] Other: ________________

**Business Criticality:**
```
[Describe how this detection relates to business-critical systems or processes]
[Identify potential business disruption if threats go undetected]
```

---

## 🔍 Technical Requirements

### 🎯 Scope and Objectives

**Primary Objective:**
```
[Clear statement of what this use case should detect or prevent]
```

**Success Criteria:**
```
[Measurable outcomes that define successful implementation]
[Include detection accuracy, response time, or coverage metrics]
```

**Out of Scope:**
```
[Explicitly state what this use case will NOT cover]
```

### 📊 Data Sources and Systems

**Required Data Sources:**
- [ ] Windows Event Logs
- [ ] Linux/Unix Logs  
- [ ] Network Traffic (NetFlow/PCAP)
- [ ] DNS Logs
- [ ] Proxy/Web Logs
- [ ] Firewall Logs
- [ ] Endpoint Detection (EDR)
- [ ] Cloud Platform Logs (AWS/Azure/GCP)
- [ ] Application Logs
- [ ] Database Logs
- [ ] Other: ________________

**Affected Systems/Assets:**
```
[List specific systems, networks, or asset types that should be monitored]
[Include IP ranges, hostnames, or system classifications]
```

### ⚔️ Threat Landscape

**Attack Techniques (MITRE ATT&CK):**
```
[Reference specific MITRE ATT&CK techniques if known]
[Example: T1566.001 - Spearphishing Attachment]
```

**Known Indicators:**
```
[List any known IOCs, patterns, or signatures]
[Include file hashes, domains, IPs, or behavioral patterns]
```

**Attack Scenarios:**
```
[Describe the attack scenarios this use case should detect]
[Include attack progression and potential impact]
```

---

## 👥 Stakeholder Information

### 🎪 Primary Stakeholders

**Business Owner:**
- **Name:** `[Name and Title]`
- **Department:** `[Department]`
- **Contact:** `[Email/Phone]`
- **Role:** `[Decision authority and responsibilities]`

**Technical Owner:**
- **Name:** `[Name and Title]`
- **Department:** `[IT/Security Team]`
- **Contact:** `[Email/Phone]`
- **Role:** `[Implementation and maintenance responsibilities]`

### 📞 Secondary Stakeholders

**Incident Response Team:**
- **Primary Contact:** `[Name and Contact]`
- **Escalation Path:** `[Escalation procedures]`

**Compliance/Legal:**
- **Contact:** `[Name and Contact if applicable]`
- **Requirements:** `[Specific compliance considerations]`

---

## 📈 Implementation Planning

### 🚀 Deployment Requirements

**Environment:**
- [ ] Production
- [ ] Staging/Test
- [ ] Development
- [ ] All Environments

**Performance Considerations:**
```
[Expected query volume, data retention requirements]
[Resource impact on SIEM/logging infrastructure]
```

**Integration Requirements:**
```
[Required integrations with ticketing, SOAR, or other systems]
[Alert routing and notification requirements]
```

### 📊 Success Metrics

**Detection Metrics:**
- **Target Detection Rate:** `[Percentage or specific threshold]`
- **Maximum False Positive Rate:** `[Acceptable percentage]`
- **Mean Time to Detect (MTTD):** `[Target timeframe]`

**Operational Metrics:**
- **Alert Volume:** `[Expected alerts per day/week]`
- **Response Time:** `[Target response timeframe]`
- **Coverage:** `[Percentage of environment covered]`

---

## 🔄 Approval and Tracking

### ✅ Approval Workflow

**Business Approval:**
- **Approved By:** `[Name and Date]`
- **Signature:** `[Digital signature or approval reference]`

**Technical Approval:**
- **Reviewed By:** `[Security Architect/Engineer Name and Date]`
- **Technical Feasibility:** `[ ] Approved [ ] Needs Review [ ] Rejected`

**Budget/Resource Approval:**
- **Approved By:** `[Manager/Director Name and Date]`
- **Resource Allocation:** `[Approved hours/budget]`

### 📋 Status Tracking

| **Phase** | **Status** | **Assigned To** | **Due Date** | **Notes** |
|-----------|------------|-----------------|--------------|-----------|
| Planning | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |
| Development A | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |
| Development B | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |
| Development C | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |
| Delivery | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |
| Improvement | `[ ] Not Started [ ] In Progress [ ] Complete` | | | |

---

## 📝 Additional Notes

**Special Considerations:**
```
[Any additional requirements, constraints, or considerations]
[Dependencies on other projects or systems]
[Regulatory or legal considerations]
```

**Related Use Cases:**
```
[Reference any related or dependent use cases]
[Identify potential conflicts or overlaps]
```

---

**Template Version:** 1.0  
**Last Updated:** [Date]  
**Framework Phase:** Planning Phase  

> 💡 **Next Steps**: After completing this template, proceed to the Technical Feasibility Analysis phase of the Detection Engineering Framework.

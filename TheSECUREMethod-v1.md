# The SECURE Method™- v1.0 - August 2025
## IEC 62443 Simplified for Industrial Networks

*"Making industrial cybersecurity standards actually usable in the real world"*

---

## **S** - **Segment Your Networks**
**IEC 62443 Reference:** Zones and Conduits (3-2)

- Separate networks by risk and function
- IT/OT boundary is the minimum requirement
- Isolate safety systems always
- Document what can't be segmented and why

> *"If everything is on one network, one breach kills everything"*

**Practical Implementation:**
- Create functional zones (production, safety, maintenance)
- Use VLANs and firewalls to enforce boundaries
- Separate critical systems from convenience systems
- Map data flows between zones and control them

---

## **E** - **Establish Security Levels**
**IEC 62443 Reference:** Security Level Targets (3-3)

- **SL-1:** Protection from accidents and human error
- **SL-2:** Protection from basic attacks and malware
- **SL-3:** Protection from sophisticated, targeted attacks
- **SL-4:** Protection from nation-state level threats

> *"Match protection to actual risk, not imaginary threats"*

**Reality Check:**
- Most facilities need SL-2 for production, SL-3 for safety systems
- SL-4 is for nuclear plants and critical infrastructure
- Don't over-engineer security that breaks operations
- Start with SL-1 and build up based on actual threats

---

## **C** - **Control Access**
**IEC 62443 Reference:** Access Control (FR1)

- **Physical Security:** Locks, badges, cameras where they matter
- **Role-Based Access:** Operator, Engineer, Admin with clear boundaries
- **Emergency Override:** When security can't prevent operations
- **Regular Audits:** Who has access to what, and why

> *"The best access control is the one people actually follow"*

**Practical Approach:**
- Lock network cabinets like you lock control rooms
- Use existing plant badge systems for network access
- Create emergency procedures that bypass security safely
- Audit permissions quarterly, not annually

---

## **U** - **Update Responsibly**
**IEC 62443 Reference:** Patch Management (2-3)

- **Risk-Based Schedule:** Critical security patches fast, everything else planned
- **Test Before Production:** Use development systems or offline testing
- **Document Exceptions:** What can't be patched and why
- **Compensating Controls:** Extra protection for unpatched systems

> *"Patch management that breaks production isn't security - it's sabotage"*

**Industrial Reality:**
- Some systems can't be patched during production
- Test patches on non-critical systems first
- Use network segmentation to protect unpatchable systems
- Schedule updates during planned maintenance windows

---

## **R** - **Respond to Incidents**
**IEC 62443 Reference:** Incident Response (2-1)

- **Priority Order:** Safety > Production > Evidence preservation
- **OT-Specific Procedures:** Don't assume IT incident response works
- **Defined Response Team:** Operations leads, IT supports
- **Practice Scenarios:** Tabletop exercises with real constraints

> *"In OT, safety trumps everything - including perfect forensics"*

**Response Framework:**
1. **Immediate:** Stop the threat, maintain safe operations
2. **Short-term:** Isolate affected systems, restore production
3. **Long-term:** Investigate, improve defenses, document lessons
4. **Continuous:** Update procedures based on what you learned

---

## **E** - **Evaluate Continuously**
**IEC 62443 Reference:** Cybersecurity Management System (2-1)

- **Monthly Health Checks:** Are your defenses still working?
- **Quarterly Assessments:** What changed, what's broken?
- **Annual Program Review:** Strategic evaluation and planning
- **Continuous Improvement:** Fix what's broken, improve what works

> *"Security isn't a project - it's an ongoing operational requirement"*

**Evaluation Cycle:**
- **Daily:** Monitor alerts and system health
- **Weekly:** Review security events and false positives
- **Monthly:** Check access permissions and system updates
- **Quarterly:** Assess threats and update procedures
- **Annually:** Strategic review and budget planning

---

## **SECURE Implementation Roadmap**

### **Phase 1: Foundation (Months 1-3)**
**Focus: Segment & Establish**
- Complete network inventory and mapping
- Implement basic segmentation between IT/OT
- Define security levels for each zone
- *Success Metric: Clear network boundaries that people understand*

### **Phase 2: Access Control (Months 4-6)**
**Focus: Control & Update**
- Deploy role-based access controls
- Establish patch management procedures
- Lock down physical access points
- *Success Metric: Only authorized people can access critical systems*

### **Phase 3: Operations (Months 7-9)**
**Focus: Respond & Evaluate**
- Create incident response procedures
- Deploy monitoring and alerting
- Conduct first tabletop exercise
- *Success Metric: Team knows what to do when something goes wrong*

### **Phase 4: Maturity (Months 10+)**
**Focus: Continuous Improvement**
- Regular security assessments
- Advanced threat detection
- Automated response capabilities
- *Success Metric: Security that improves operations instead of hindering it*

---

## **SECURE vs. Traditional IT Security**

| Aspect | Traditional IT | SECURE Method |
|--------|----------------|---------------|
| **Priority** | Confidentiality first | Availability first |
| **Patching** | Patch immediately | Test, then patch during maintenance |
| **Access** | Role-based complexity | Function-based simplicity |
| **Monitoring** | Log everything | Monitor what matters to operations |
| **Response** | Preserve evidence | Stop the threat, maintain safety |
| **Compliance** | Checkbox security | Risk-based implementation |

---

## **Common SECURE Implementation Mistakes**

### **What Doesn't Work:**
- Copying IT security policies directly to OT
- Implementing security that requires constant IT support
- Choosing tools based on features instead of operational fit
- Assuming all OT systems can be patched like IT systems

### **What Does Work:**
- Security policies written by operations for operations
- Simple, reliable security that plant personnel can maintain
- Tools that integrate with existing operational procedures
- Risk-based security that matches actual threats

---

## **SECURE Success Metrics**

### **Technical Metrics:**
- **Segmentation:** Clear network boundaries with documented exceptions
- **Access Control:** Regular access audits with prompt cleanup
- **Patch Management:** Defined process with measurable compliance
- **Incident Response:** Mean time to containment under 15 minutes

### **Operational Metrics:**
- **Production Impact:** Security incidents causing zero unplanned downtime
- **User Adoption:** Security procedures followed without workarounds
- **Cost Effectiveness:** Security investment showing measurable ROI
- **Continuous Improvement:** Regular updates based on lessons learned

---

## **Integration with Other Methods**

**SECURE + SHIP Framework:**
- **Standardize:** Consistent security policies across all zones
- **Harden:** Security measures that improve system reliability
- **Isolate:** Segmentation that supports both security and operations
- **Protect:** Comprehensive security without operational disruption

**SECURE + STREAM Troubleshooting:**
- Security incidents are network problems requiring systematic investigation
- STREAM methodology applies to security incident response
- Both methods prioritize operational continuity over perfect solutions

---

*© 2025 Danny "Riverman" Caudle


Backward communication is allowed ONLY as feedback, not control.

Example:

- QA → Backend (bug report)
- Review → Team Lead (revision request)

---

## 4. Feedback vs Control

- **Feedback**: Suggests change, does not enforce
- **Control**: Can stop or redirect execution

Only these agents have control authority:

- Human / Product Owner
- Review & Audit Agent
- CTO Agent (technical scope only)

All others provide feedback only.

---

## 5. Conflict Resolution

When conflicts arise:

1. Identify the conflicting outputs
2. Document the conflict explicitly
3. Escalate to Review & Audit Agent
4. If unresolved, request human input

Conflicts are never resolved silently.

---

## 6. Traceability Requirement

All major decisions must be traceable to:

- An agent
- An explicit output
- A documented assumption

This enables later review, audit, and learning.

---

## 7. Model Intent

This communication model exists to:

- Reduce hallucination risk
- Prevent hidden assumptions
- Enable safe automation in future versions
- Make multi-agent behavior understandable and debuggable

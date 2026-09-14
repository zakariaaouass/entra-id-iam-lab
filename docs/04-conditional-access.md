# 04 — Conditional Access

## Goal
Create a safe test Conditional Access policy and understand its evaluation model.

## Suggested lab policy

Name: `CA-LAB-MFA-Test-Users`

Scope: dedicated lab users only

Control: require MFA

Testing approach: use report-only mode before enabling a disruptive policy.

## Safety

Always protect a break-glass / recovery path in a real tenant. Do not apply an experimental policy broadly.

## Evidence checklist

- [ ] Policy created
- [ ] Scope documented
- [ ] Grant control documented
- [ ] Report-only evaluation reviewed
- [ ] No production accounts included

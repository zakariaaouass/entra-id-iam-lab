# 02 — RBAC and Least Privilege

## Scenario

Contoso Labs wants access to be assigned by business role rather than individually wherever practical.

## Proposed model

| Business role | Group | Example access |
|---|---|---|
| Sales User | `SG-Sales-Users` | Sales application |
| Finance User | `SG-Finance-Users` | Finance application |
| IT Support | `SG-IT-Support` | Support tooling |

## IAM principles demonstrated

- Group-based access assignment
- Role-based access control (RBAC)
- Least privilege
- Separation of privileged administration from normal user access

## Evidence checklist

- [ ] Groups created
- [ ] Members assigned
- [ ] Access granted through groups where possible
- [ ] Privileged role assignments reviewed
- [ ] Decisions documented

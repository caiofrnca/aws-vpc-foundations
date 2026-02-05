### AWS VPC Foundations

This repository demonstrates progressive mastery of AWS VPC architecture, networking, and security boundaries through
incremental builds.

Each build introduces a new architectural concept and explains design decisions, trade-offs, and security implications.

- What this repo is
- Why VPC matters
- How builds progress
- What skills this proves

--

#### Structure
```bash
aws-vpc-foundations/
├── README.md
├── build-1-vpc-baseline/
├── build-2-public-private-subnets/
├── build-3-routing-igw-nat/
├── build-4-security-groups-vs-nacls/
└── build-5-bastion-access-pattern/
```
and inside every build folder:
```bash
build-X-name/
├── README.md          ← explanation 
├── architecture.png   ← diagram 
├── notes.md           ← decisions & trade-offs
└── screenshots/       ← AWS console proof
```

--
# Security policy

At Verify Everything, an **unsound proof or an overstated claim card is a security issue**. Someone may rely on that claim.

## Reporting

Please report privately using GitHub's **Report a vulnerability** button on the affected repository (Security tab → Advisories). Don't open a public issue.

Please include:

- the entry (`libs/<library>/<version>`) and the claim affected;
- what is wrong: an unsound proof, a spec that doesn't say what the claim card says, a gap missing from **Not covered**, or a broken pipeline that still shows as `verified`;
- how to reproduce it, if you can.

## What happens next

We confirm the report, mark the entry `status: broken` (or correct the claim card) while it's being fixed, and credit you in the advisory if you'd like.

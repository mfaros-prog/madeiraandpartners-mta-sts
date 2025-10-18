# MTA-STS Policy for madeiraandpartners.com

This repo serves the `.well-known/mta-sts.txt` file for Madeira & Partners’ domain via GitHub Pages.

## Update Process
1. Edit `.well-known/mta-sts.txt` if MX records change.
2. Commit changes to `main` branch.
3. Increment the `id=` value in the `_mta-sts` TXT record in GoDaddy (e.g., `id=20251101T0000Z`).
4. Verify live at: https://mfaros-prog.github.io/madeiraandpartners-mta-sts/.well-known/mta-sts.txt

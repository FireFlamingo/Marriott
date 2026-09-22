# Marriott bug bounty research

Official program: https://hackerone.com/marriott

Official scope: https://hackerone.com/marriott/policy_scopes

`scope.csv` is the official HackerOne export downloaded on 2026-09-23 from `https://hackerone.com/teams/marriott/assets/download_csv.csv`. Check the live scope before testing because the program can change it. The export contains 109 assets, of which 78 are eligible for submission and 77 are bounty eligible.

## Rules relevant to this research

- Assets not explicitly listed in scope are ineligible. Do not test listed out-of-scope assets, including `globaldesign.marriott.com/*`, `gdstest.marriott.com`, and `ofhub.marriott.com`.
- The program excludes reflected and DOM XSS, web cache poisoning, open redirects and content spoofing without persistent modification, leaked tokens without demonstrated account takeover, denial of service, physical-network attacks, and recently patched zero-days. See the live policy for the full wording.
- Stop testing and notify Marriott through HackerOne if personal or confidential data or another person's account is accessed. Keep submissions and related information confidential. The policy says supporting evidence belongs only in the HackerOne submission.
- Submission requirements include the affected asset and owner, reproducible proof, remediation, testing dates, public IP address, browser, tools, and app version when applicable.

The maximum severity and bounty eligibility for each asset are in `scope.csv`; a maximum severity is a cap, not a finding. No vulnerability is confirmed by this file.

Disposable inbox service used for the synthetic test account: [Mail.tm](https://mail.tm/). Account credentials stay in the ignored local `.env` file.

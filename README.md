# [Sponsorname] Audit

Audit findings are submitted and stored in Code4rena.

Unless otherwise discussed, these findings will be made public after audit completion, sponsor review, judging, and issue mitigation window.

**Note that when the findings are made public, after all issues are mitigated, your comments will be publicly visible; they may also be included in your C4 audit report.**

---

# Review phase

Sponsors have three key inputs in the audit process: Reviewing the two lists of triaged findings, and once you have mitigated them, sharing those mitigations. 

1. [Respond to triaged High- and Medium-risk findings ↓](#1-respond-to-triaged-high--and-medium-risk-findings)
2. [Respond to triaged Low-risk findings ↓](#2-respond-to-triaged-low-risk-findings)
3. [Share your mitigation of findings (optional) ↓](#3-share-your-mitigation-of-findings-optional)

<hr>
<details>
<summary>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<h2>Types of findings</h2> (expand to read more)</summary>

### High- or Medium-risk findings

Wardens cannot see each other's submissions, so keep in mind that there will always be duplicates. All `High` and `Medium` risk submissions have been triaged for you, into unique groups called **findings**. In each unique finding, only the highest quality submission, marked as the `primary`, will be shown to you by default. You can also expand findings to see all duplicate submissions inside, if you choose.

### QA reports and Gas reports

Any warden submissions in these two categories are submitted as bulk listings of issues and recommendations:

- **[QA reports](https://docs.code4rena.com/awarding/judging-criteria#qa-reports-low-risk-and-governance-centralization-risk)** include *all* low severity findings and governance/centralization risk findings from an individual warden.
- **[Gas reports](https://docs.code4rena.com/awarding/judging-criteria#gas-reports)** (if applicable) include *all* gas optimization recommendations from an individual warden.
</details>
<hr>

## 1. Respond to triaged High- and Medium-risk findings

For each triaged High- or Medium-risk finding, please:

### 1a. Add your review as one of the following:

- `confirmed`, meaning: "Yes, this is a problem and we intend to fix it."
- `disputed`, meaning either: "We cannot duplicate this issue" or "We disagree that this is an issue at all."
- `acknowledged (wontfix)`, meaning: "Yes, technically the issue is correct, but we are not going to resolve it for xyz reasons."

Add any necessary comments explaining your rationale for your evaluation of the issue.

### 1b. Weigh in on severity

If you believe a finding is technically correct but disagree with the listed severity, **leave a comment indicating your reasoning** for the judge to review.
For a detailed breakdown of severity criteria and how to estimate risk, please refer to the [judging criteria in our documentation](https://docs.code4rena.com/awarding/judging-criteria/severity-categorization).

Judges have the ultimate discretion in determining validity and severity of submissions, as well as whether/how submissions are considered duplicates. However, sponsor input is a significant criterion.

<hr>

## 2. Respond to triaged Low-risk findings

- Leave a comment for the judge on any reports you consider to be particularly high quality.
- Review any reports as `disputed` that you think should be completely disregarded by the judge, i.e. the report contains no valid findings at all.

## Once Step 1 and 2 are complete

When you have finished reviewing findings, drop a note in your private backroom channel to let the C4 team know. At this point, we will have the judge review your feedback while you work on mitigations.


<hr>

## 3. Share your mitigation of findings (Optional)

Once you have confirmed the findings you intend to mitigate, you will want to address them before tha audit report is made public. Linking your mitigation PRs to your audit findings enables us to include them in your C4 audit report. 

*Note: You can work on your mitigations during the judging phase -- or beyond it, if you need more time. We won't publish the final audit report until you give us the OK.*

### If you are planning a Code4rena mitigation review:

1. In your own GitHub repo, create a branch based off of the commit you used for your Code4rena audit, then
2. Create a separate Pull Request for each **High or Medium risk** C4 audit finding that you confirmed (e.g. one PR for finding H-01, another for H-02, etc.)
3. Link the PR to the finding that it resolves.

Most C4 mitigation reviews focus exclusively on reviewing mitigations of High and Medium risk findings. Therefore, QA and Gas mitigations should be done in a separate branch. If you want your mitigation review to include QA or Gas-related PRs, please reach out to C4 staff and let’s chat!

If several findings are inextricably related (e.g. two potential exploits of the same underlying issue, etc.), you may create a single PR for the related findings.

### If you aren’t planning a mitigation review

1. Within a repo in your own GitHub organization, create a pull request for each finding.
2. Link the PR to the finding that it resolves.

This will allow for complete transparency in showing the work of mitigating the issues found in the audit.

# A6.2 Simplified provider-verification prompt

> This reproduces Appendix 6 (A6.2) from the thesis. It includes the simplified verification prompt and the documented workflow.

After the first provider datasets had been prepared, a shorter instruction was used for the
verification stage. The provider name, workbook, screenshots, screen recordings, and

links changed between research sessions, while the core instruction remained the same.

Prompt:

Use the simplified provider dataset verification process below for [provider]. First,
inspect the uploaded workbook and give me a maximum of 5-7 high-value checks. Do not
                                                                    111




create a comprehensive testing plan, and do not require paid workloads. I will upload
evidence in batches, and you should update the workbook only after I say “finalize
and update the workbook.”

Applied verification workflow

The simplified instruction was applied in five stages.

1. Initial workbook review

The existing provider workbook was inspected before new checks were proposed. The

purpose was to identify the most important gaps, contradictions, or claims that could be
checked without reproducing the full original research process.

2. Selection of high-value checks

A maximum of five to seven checks were proposed for each provider. The exact checks

depended on the existing evidence and the degree of platform access. They could cover:

   ●  signup and onboarding;
   ●  account, project, or organization structure;

   ●   visible GPU or service catalogs;
   ●  pricing and availability presentation;

   ●   billing, quota, or usage screens;
   ●  deployment and configuration workflows;

   ●  storage and network options;

   ●  Kubernetes or Slurm-related surfaces;
   ●  model, inference, or notebook interfaces;

   ●  APIs or access-key management;
   ●  documentation quality;

   ●  status pages, support channels, and SLA information; and
   ●  security or compliance material.

A provider was not required to expose every area. The checks were selected according to

the most important uncertainties in its workbook.

3. Evidence supplied in batches
                                                                    112



The author supplied evidence through screenshots, recordings, links, observations, and
descriptions of access restrictions. Each batch was compared with the existing workbook.

New evidence could confirm an earlier entry, narrow the claim, reveal a contradiction, or

show that a feature remained outside the verification boundary.

The workbook was not finalized after every evidence batch. This allowed later screenshots

or recordings to be considered before earlier conclusions were changed.

4. Verification boundaries

The verification process was limited to no-cost or low-risk observation. A paid GPU
workload was not required. Performance benchmarking was outside the process.

A visible interface confirmed only that the surface was available at the time of

observation. It did not by itself confirm:

   ●  current GPU inventory;

   ●  successful production provisioning;
   ●  multi-node workload execution;

   ●  runtime performance;
   ●  network or storage throughput;

   ●   final billing behavior;

   ●  long-term uptime;
   ●  support response quality; or

   ●  delivery of the published SLA.

Payment-card requirements, quota restrictions, business-account requirements, sales

approval, regional restrictions, identity checks, and other access gates were recorded as
evidence about the provider’s access model. They were not treated as proof that the

underlying technical capability was absent.

The author was not required to purchase workloads or complete intrusive identity
verification solely to obtain deeper access. Where such a boundary was reached, the

exact limitation was recorded in the provider workbook.

5. Explicit finalization
                                                                    113



The workbook was updated only after the author gave the instruction:

“Finalize and update the workbook.”

At that stage, the collected evidence was applied across the relevant technical, market,

risk, access, source-coverage, and summary sheets. The update also checked for stale
statements, especially claims that no researcher access or verification had occurred

when parts of the signup process, console, documentation, or configuration workflow had
in fact been observed.

The resulting workbook recorded both the verified surface and its boundary. For example,
console access could be confirmed while workload provisioning remained unverified.

Source: author’s provider-verification instructions and research records.

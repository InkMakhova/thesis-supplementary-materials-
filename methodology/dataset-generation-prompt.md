# A6.1 Condensed original dataset-generation prompt

> This is the **condensed** dataset-generation prompt reproduced in Appendix 6 (A6.1) of the thesis, not a verified verbatim copy of the full original prompt.

Research purpose and provider group

You are conducting detailed competitor research for a thesis and strategic competitor
analysis of cloud and neocloud GPU infrastructure companies.

The purpose is to build a large, evidence-based dataset for comparing the technical
capabilities and market positioning of GPU cloud, AI cloud, and neocloud providers.
The dataset will later support structured comparison, charts, scoring, and analysis
of provider strengths, gaps, and positioning patterns.

Research the following provider units:

   ●   Firmus;
   ●   Lambda;
   ●   Together.ai;
   ●   Core42 / G42;
   ●   Vultr;
   ●   Voltage Park;
   ●   Scaleway;
   ●   TensorWave;
   ●   GMO GPU Cloud;
   ●   Prime Intellect;
   ●   Verda / DataCrunch;
   ●   Gcore;
   ●   FPT Smart Cloud / FPT AI Factory;
   ●   Bitdeer AI;
   ●   GMI Cloud;
   ●   Cirrascale;
   ●   Shadeform;
   ●   Radiant / Ori;
   ●   Neysa; and
   ●   Lightning AI.

For each provider, prepare:
                                                                    101




   ●   a Technical Capabilities Evidence Pack;
   ●   a Market Positioning Evidence Pack;
   ●   normalized cross-provider dataset rows;
   ●   a source index;
   ●   a record of caveats and missing evidence; and
   ●   suggestions for later charts and comparisons.

Related brands, rebrandings, acquisitions, and organizational transitions should be
recorded carefully. They may be combined into one analytical provider unit where they
represent a continuous service and separate treatment would duplicate the same
competitor.

Research date and evidence principles

Use live web research rather than relying on model memory. Record the publication
date and accessed date of each source. Include material developments available by the
research date, such as product changes, funding, partnerships, outages,
infrastructure announcements, regulatory issues, and positioning changes.

Every meaningful statement must be connected to an identifiable source. Keep the
following evidence types separate:

   ●   researcher-tested or researcher-observed evidence;
   ●   external technical reviews;
   ●   official provider claims;
   ●   official technical documentation;
   ●   official pricing or legal material;
   ●   partner confirmation;
   ●   customer confirmation;
   ●   independent media reporting;
   ●   financial or database estimates;
   ●   public registries or filings;
   ●   social or other weak signals;
   ●   rumors or unconfirmed information; and
   ●   current capability versus announced or future capability.

Do not treat marketing claims as verified facts. Do not count announced GPU capacity
as current deployable capacity. Do not infer dashboard usability, provisioning
quality, pricing transparency, SLA performance, workload execution, or production
reliability without suitable evidence.

The study does not require performance benchmarking. Where platform access is
possible, propose feature-verification checks rather than NCCL, MLPerf, throughput,
latency, storage-performance, or similar benchmark tests.

Source requirements

Search broadly and continue until repeated searches stop producing materially new
evidence. For providers with substantial public coverage, the original prompt
suggested approximately 40 or more source candidates where available. This was a
search-breadth target rather than a required minimum. Source quality remained more
important than the number of sources.

Use the following source groups.

1. Official provider sources

These may include:

   ●   company and product websites;
   ●   GPU cloud and bare-metal pages;
   ●   Kubernetes, Slurm, storage, and networking pages;
   ●   pricing pages;
   ●   documentation portals;
   ●   API, command-line, SDK, and infrastructure-as-code documentation;
   ●   blogs, newsrooms, and press releases;
   ●   status pages and incident information;
   ●   SLA and support terms;
   ●   trust centres;
                                                                    102




   ●   security and compliance pages;
   ●   customer case studies;
   ●   terms of service and acceptable-use policies; and
   ●   careers pages where they provide relevant information about products, regions,
       or target customers.

2. ClusterMAX and SemiAnalysis sources

Review:

   ●   the relevant ClusterMAX ranking;
   ●   the ClusterMAX methodology and criteria;
   ●   provider-specific reviews where available;
   ●   related SemiAnalysis articles;
   ●   the ClusterMAX version and publication date; and
   ●   changes between benchmark versions where these affect the provider group.

ClusterMAX evidence must remain separate from the thesis assessment. Its conclusions
should not be copied directly into the final comparison score.

3. Independent technical and industry sources

Use credible technical reviews, infrastructure analysis, industry publications,
conference material, independent testing, and other sources that may confirm or
challenge provider claims.

4. Financial and company sources

Where relevant, use:


   ●   official investor-relations material;
   ●   company registries and public filings;
   ●   official funding announcements;
   ●   investor or legal-adviser announcements;
   ●   reputable business and financial media; and
   ●   commercial databases such as PitchBook, Crunchbase, Dealroom, Tracxn, or
       similar services.

Commercial database values should be marked as estimates unless another source
confirms them.

5. Partner and ecosystem sources

Search for evidence from:

   ●   NVIDIA, AMD, Intel, and server manufacturers;
   ●   storage and networking companies;
   ●   data-centre operators;
   ●   connectivity, fibre, energy, and cooling partners;
   ●   software ecosystems and cloud marketplaces;
   ●   resellers and channel partners; and
   ●   public partner or joint-customer announcements.

6. Customer and target-market sources

Review:

   ●   customer case studies;
   ●   named customer announcements;
   ●   public contracts and procurement awards;
   ●   government tenders;
   ●   university and research partnerships;
   ●   enterprise and AI-laboratory partnerships;
   ●   startup and independent software vendor programmes; and
   ●   reseller or channel material.

A customer logo alone should be treated cautiously unless the relationship is
explained by a credible source.
                                                                    103




7. Risk and negative-signal sources

Search for:

   ●   outages and incident history;
   ●   legal disputes;
   ●   sanctions or export-control issues;
   ●   environmental and construction permits;
   ●   community opposition;
   ●   power, water, and other resource constraints;
   ●   construction delays;
   ●   financing stress;
   ●   credible customer complaints;
   ●   security incidents; and
   ●   other negative reporting relevant to provider execution or positioning.

8. Social and weak sources

LinkedIn, X, Reddit, forums, YouTube, Discord, and similar sources may be used as
supplementary signals. They should normally receive low or medium confidence and
should not be the sole basis for an important claim.

Searches for each provider should cover, where relevant:

   ●   GPU cloud and AI cloud services;
   ●   current GPU models and pricing;
   ●   Kubernetes and Slurm;
   ●   API, command-line, SDK, and Terraform support;
   ●   NVIDIA partnerships;
   ●   funding, valuation, and investors;
   ●   data-centre locations, power, and energy;
   ●   customers and case studies;
   ●   outages, status pages, and SLA terms;
   ●   security and compliance;
   ●   ClusterMAX and SemiAnalysis coverage;
   ●   legal or regulatory issues; and
   ●  the latest company and independent news.

Evidence classification

Assign an evidence type, verification status, evidence-strength level, and date to
each material claim or observation.

Evidence types

Allowed evidence types include:

   ●   Researcher tested;
   ●   External technical review;
   ●   Official product claim;
   ●   Official documentation;
   ●   Official pricing page;
   ●   Official infrastructure announcement;
   ●   Official funding announcement;
   ●   Independent news;
   ●   Partner confirmation;
   ●   Customer confirmation;
   ●   Financial database estimate;
   ●   Public registry or filing;
   ●   Public access observation;
   ●   Social or weak signal; and
   ●   Rumor or unconfirmed information.

Verification statuses

Allowed verification statuses include:

   ●   Researcher tested;
   ●   Externally tested or reviewed;
                                                                    104




   ●   Officially documented but not tested;
   ●   Partner or customer corroborated;
   ●   Independent media corroborated;
   ●   Publicly observable;
   ●   Future or announced;
   ●   Not found;
   ●   Conflicting evidence; and
   ●   Unverified.

Evidence strength

High: direct and current official documentation with strong confirmation; an audited
or regulatory filing; a relevant hands-on external review; a named customer
confirmation; or a current pricing or SLA source.

Medium: an official product or marketing page, credible media source, partner
article, financial database, or another credible claim that has not been
independently verified.

Low: a social post, forum comment, vague marketing statement, unclear or outdated
source, rumor, or other claim that cannot be verified.

Evidence strength shows how well a claim is supported. It does not show whether the
finding is favorable. A directly observed access restriction can have high evidence
strength while still indicating poor accessibility.

Freshness

Record the source publication date and the accessed date. Flag product, pricing,
availability, partnership, or market information that may be outdated. Prefer recent
evidence where available and conduct a final latest-news check for each provider.

Technical Capabilities Evidence Pack

Create a separate technical evidence pack for each provider.

Sheet 1: Executive Summary

Include:

   ●   provider name and related brands;
   ●   research date;
   ●   evidence-status summary;
   ●   ClusterMAX tier, version, and publication date;
   ●   researcher access status;
   ●   public self-service availability;
   ●   main technical conclusion;
   ●   strongest documented or observed capabilities;
   ●   main technical gaps;
   ●   unusual or differentiated features;
   ●   current capabilities compared with announced future capabilities;
   ●   recommended treatment in the thesis; and
   ●   key caveats.

Sheet 2: Capability Evidence Matrix

Use one row for each material technical claim or observation. The main fields should
include:

   ●   evidence ID;
   ●   provider;
   ●   ClusterMAX dimension;
   ●   capability category and topic;
   ●   claim or observation;
   ●   exact capability details;
   ●   current, announced, future, or unknown status;
   ●   evidence type;
   ●   verification status;
   ●   evidence strength;
                                                                    105




   ●   source name and URL;
   ●   publication and accessed dates;
   ●   possible thesis use;
   ●   comparable variable;
   ●   caveat or limitation; and
   ●   any required follow-up verification.

Map technical evidence to the ten ClusterMAX areas:

   ●   Security;
   ●   Lifecycle;
   ●   Orchestration;
   ●   Storage;
   ●   Networking;
   ●   Reliability;
   ●   Monitoring;
   ●   Pricing;
   ●   Partnerships; and
   ●   Availability.

Add more detailed capability categories where useful. These may include:

   ●   onboarding and account access;
   ●   self-service signup;
   ●   console or dashboard;
   ●   GPU instance types;
   ●   bare metal and virtual machines;
   ●   reserved or interruptible capacity;
   ●   managed and multi-node clusters;
   ●   inference services;
   ●   Kubernetes, Slurm, Ray, and batch jobs;
   ●   containers and images;
   ●   notebooks and development studios;
   ●   CUDA, drivers, and machine-learning frameworks;
   ●   model hosting and inference microservices;
   ●   API, command-line, SDK, and Terraform support;
   ●   object, block, shared, parallel, and local storage;
   ●   RDMA, GPUDirect, InfiniBand, Ethernet, NVLink, and NVSwitch;
   ●   virtual private networking, firewalls, IAM, RBAC, MFA, SSO, and audit logs;
   ●   encryption and compliance;
   ●   SLA, support, and status communication;
   ●   billing, quota, and cost visibility;
   ●   observability and health information;
   ●   managed services and marketplace integrations;
   ●   regions and infrastructure locations;
   ●   capacity and allocation claims; and
   ●   documentation quality.

Sheet 3: Differentiated features outside the main benchmark

Record unusual features that may be strategically important even when they do not fit
neatly into the ten main technical areas. Examples include:

   ●   proprietary or liquid-cooling systems;
   ●   energy-aware or carbon-aware scheduling;
   ●   power-market integration;
   ●   a sovereign AI-factory model;
   ●   special NVIDIA roadmap alignment;
   ●   hybrid or on-premises services;
   ●   model or inference marketplaces;
   ●   managed fine-tuning;
   ●   reusable model, RAG, NIM, or agent templates;
   ●   a specialized storage stack;
   ●   startup or AI-laboratory programmes;
   ●   a reserved-capacity marketplace;
   ●   vertically integrated data-centre design;
                                                                    106




   ●   unusual power or connectivity arrangements; and
   ●   distinctive pricing or financing models.

Record whether each feature is current or announced and explain its technical and
market relevance.

Sheet 4: ClusterMAX external evidence

Keep the ClusterMAX version, tier, observation, capability implication, source,
thesis use, and caveat in a separate record. ClusterMAX evidence should support
context and triangulation rather than replace the thesis assessment.

Sheet 5: Access and testing status

Record:

   ●   researcher access;
   ●   public signup;
   ●   console login;
   ●   documentation access;
   ●   API-key access;
   ●   pricing visibility;
   ●   free trial or credits;
   ●   sales-gated access;
   ●   status of technical claims;
   ●   availability of third-party review;
   ●   action to take when access is granted; and
   ●   treatment when access is unavailable.

Sheet 6: Feature-verification checklist

Where platform access is available, check selected high-value service surfaces, such
as:

   ●   signup and approval;
   ●   the first dashboard screen;
   ●   documentation coverage;
   ●   visible instance and GPU catalogs;
   ●   driver or CUDA information;
   ●   Kubernetes and Slurm availability;
   ●   storage and object-storage options;
   ●   IAM, RBAC, and MFA;
   ●   cost and quota screens;
   ●   support or ticket workflows;
   ●   SLA and status communication;
   ●   observability; and
   ●   cleanup or termination controls.

Do not require NCCL, MLPerf, throughput, latency, or other performance benchmarks
unless the researcher makes a separate decision to conduct them.

Sheets 7–9

Maintain:

   ●   a source index;
   ●   a caveat register; and
   ●   an evidence legend defining the permitted evidence, verification, strength,
       current/future, and thesis-use values.

Market Positioning Evidence Pack

Create a separate market-positioning evidence pack for each provider.

Sheet 1: Executive Summary

Include:

   ●   provider name and related brands;
   ●   research date;
   ●   high-level market conclusion;
                                                                    107




   ●   proposed positioning archetype;
   ●   main customer segments;
   ●   geographic focus;
   ●   main differentiation;
   ●   business model;
   ●   public or private status;
   ●   founding and location information;
   ●   approximate employee count;
   ●   disclosed funding and valuation;
   ●   main investors;
   ●   NVIDIA relationship;
   ●   major partners;
   ●   customers or demand signals;
   ●   sustainability and energy positioning;
   ●   main risks;
   ●   main implication for the thesis; and
   ●   the evidence status of the provider’s technical claims.

Sheet 2: Key Evidence Matrix

Use one row for each important positioning fact. Record:

   ●   theme;
   ●   evidence or data point;
   ●   relevance to the positioning matrix;
   ●   source type and reliability;
   ●   date and URL;
   ●   current, future, or historical status;
   ●   comparable variable; and
   ●   caveat.

Themes may include company identity, founding, headquarters, employee estimate,
business model, product model, target segments, geographic presence, GPU supply,
data-centre footprint, energy and power, funding, valuation, investors, debt,
partners, customers, sovereignty, enterprise focus, developer focus, training,
inference, marketplace logic, sustainability, pricing, financial transparency,
acquisition or public-listing signals, risks, and latest news.

Sheet 3: Timeline and Funding

Record dated developments such as:

   ●   founding;
   ●   product launches;
   ●   major GPU deployments;
   ●   equity and debt financing;
   ●   reported valuations;
   ●   acquisitions;
   ●   data-centre announcements;
   ●   energy agreements;
   ●   strategic partnerships;
   ●   large customer contracts;
   ●   public-listing or acquisition events;
   ●   material negative events; and
   ●   recent news.

Each row should include the date, event, amount or scale, valuation where relevant,
investors or partners, strategic meaning, source, evidence type, and caveat.

Sheet 4: Partners and Ecosystem

Record partners and other ecosystem signals. Partner types may include:

   ●   NVIDIA;
   ●   AMD or Intel;
   ●   data-centre operators;
   ●   server manufacturers;
   ●   storage and networking partners;
                                                                    108




   ●   energy, cooling, and connectivity partners;
   ●   investors;
   ●   customers;
   ●   governments;
   ●   cloud marketplaces;
   ●   software ecosystems;
   ●   resellers; and
   ●   community or risk stakeholders.

For each relationship, record the evidence, positioning implication, confidence,
current or announced status, source, and caveat.

Sheet 5: NVIDIA Relationship Deep Dive

Record whether the provider is publicly identified as:

   ●   an NVIDIA Cloud Partner;
   ●   an NVIDIA investment target;
   ●   an NVIDIA customer;
   ●   aligned with current NVIDIA GPU platforms or roadmaps; and
   ●   integrated with NVIDIA software.

Keep DGX, HGX, GB200, GB300, Blackwell, Rubin, and similar references separate and
explain the strength and limits of the evidence.

Sheet 6: Customer and Target Focus

Assess evidence for customer groups such as:

   ●   hyperscale AI laboratories;
   ●   frontier-model training;
   ●   AI-native startups;
   ●   enterprise AI;
   ●   independent software vendors;
   ●   inference platforms;
   ●   government or sovereign AI;
   ●   defence or secure workloads;
   ●   research, university, and HPC customers;
   ●   media and rendering;
   ●   life sciences;
   ●   financial services; and
   ●   general developer self-service.

Named and anonymous customer evidence should remain separate.

Sheet 7: Geographic and Infrastructure Footprint

Record:

   ●   country or region;
   ●   city or data-centre location;
   ●   current or announced status;
   ●   stated GPU capacity;
   ●   power capacity where disclosed;
   ●   data-centre partner;
   ●   networking or fibre information;
   ●   energy source;
   ●   availability status;
   ●   source; and
   ●   caveat.

Sheet 8: Positioning Scores

Use a 1–5 scale, with a rationale, source, confidence level, and caveat for every
value. The criteria may include:

   ●   training focus;
   ●   inference focus;
   ●   enterprise or hyperscale focus;
                                                                    109




   ●   startup and developer focus;
   ●   government or sovereignty focus;
   ●   geographic reach;
   ●   capital strength and execution credibility;
   ●   NVIDIA ecosystem strength;
   ●   customer validation;
   ●   partner ecosystem depth;
   ●   technical-platform maturity signal;
   ●   pricing transparency;
   ●   availability or capacity signal;
   ●   sustainability and energy differentiation;
   ●   energy or grid positioning;
   ●   marketplace or aggregation logic;
   ●   public financial transparency;
   ●   brand visibility;
   ●   stakeholder or community risk; and
   ●   AI-native or independent software vendor access.

The direction of every score must be clear. For stakeholder or community risk, a
value of 5 means low visible risk and a value of 1 means high visible risk.

Sheet 9: Latest News

Include material official and independent updates available by the research cut-off,
especially product, funding, partnership, capacity, outage, regulatory, and market-
positioning developments.

Sheet 10: Risks and Caveats

Consider:

   ●   private-company financial opacity;
   ●   uncertainty in employee estimates;
   ●   unconfirmed revenue;
   ●   announced capacity that is not yet operating;
   ●   customer names that cannot be verified;
   ●   dependence on GPU supply;
   ●   energy and power constraints;
   ●   permitting or community opposition;
   ●   construction risk;
   ●   export-control or regulatory risk;
   ●   sales-gated access;
   ●   unclear pricing;
   ●   unclear SLA terms; and
   ●   overreliance on provider marketing.

Normalized cross-provider tables

Prepare the following spreadsheet-ready tables:

   ●   Company Master — company identity, related brands, location, ownership,
       provider and positioning archetype, ClusterMAX information, and evidence
       confidence.
   ●   Technical Summary — provider, ClusterMAX dimension, score, evidence strength,
       verification status, positive evidence, gap, source, and caveat.
   ●   GPU and Capacity Claims — GPU model, current or announced status, quantity,
       region, availability, source, and caveat.
   ●   Funding and Valuation — date, financing type, amount, valuation, investors,
       source, confidence, and caveat.
   ●   Partnerships — partner, type, relationship, current or announced status,
       importance, source, and caveat.
   ●   NVIDIA Relationship — partner status, investment relationship, roadmap
       alignment, software integration, strength, source, and caveat.
   ●   Target Focus — customer segment, focus score, evidence, source, and caveat.
   ●   Geography and Infrastructure — country, location, current or announced status,
       data-centre partner, power, GPU capacity, connectivity, energy, source, and
       caveat.
                                                                    110




   ●   Pricing and Availability — public pricing, signup model, sales gate, trial or
       credits, commitment requirements, availability signal, source, and caveat.
   ●   News Timeline — date, event, event type, direction, strategic implication,
       source, and reliability.
   ●   Risks — category, risk description, severity, evidence, and treatment in the
       thesis.
   ●   Source Coverage — number and type of sources, completeness estimate, and
       missing evidence.

Wording rules

Use cautious and source-specific wording, such as:

   ●   “The company states…”
   ●   “Public documentation describes…”
   ●   “ClusterMAX reports…”
   ●   “Independent media reported…”
   ●   “A partner source confirms…”
   ●   “No public evidence was found for…”
   ●   “The item appears to be announced future capacity rather than current
       deployable capacity.”
   ●   “This was not verified by the researcher.”
   ●   “This should be treated as a positioning signal rather than technical
       verification.”

Avoid unsupported statements such as:

   ●   “The platform provides…” when the feature is neither documented nor observed;
   ●   “The company has X GPUs available now” when only an announcement exists;
   ●   “The company is certified” without a certificate, trust centre, audit report,
       or official compliance source;
   ●   “Customer X uses the platform” when the relationship is not explained by a
       credible source; and
   ●   “best”, “fastest”, or “most reliable” without a stated benchmark and
       methodology.

Required outputs

For each provider, deliver:

   ●   Technical Capabilities Evidence Pack;
   ●   Market Positioning Evidence Pack;
   ●   normalized cross-provider dataset rows;
   ●   source index;
   ●   caveats and missing-evidence record; and
   ●   suggested chart ideas.

The outputs should preserve links to the original provider and third-party sources.
AI-generated summaries are working research records and should not be treated as
independent evidence.
Source: author-developed prompt framework used for the initial provider research.

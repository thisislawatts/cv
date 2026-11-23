# Luke Watts

* [+31 (0)&thinsp;624 882 690](tel:0031624882690)  
* [luke@bestemployeeever.com](mailto:luke@bestemployeeever.com)
* [linkedin.com/in/thisislawatts](https://www.linkedin.com/in/thisislawatts)

I am a creative problem solver with 15 years experience in product and agency environments, , most recently leading platform, security and compliance work. I enjoy learning new tools and technologies, for critical business projects and for research.

I like projects I can follow from start to finish, beginning with loose requirements or a quick sketch and working with others to build something of real value. I work well in a team or on my own. My focus is on making things that are useful to people.

## Tools & Technologies

- **Ways of Working** – Shape Up, TDD, decision records, blameless post-mortems, mentoring & coaching
- **Agentic Coding** – supervised agent workflows, sandboxed autonomous agent environments, reusable skills & reviewing agent output
- **Languages** – TypeScript, JavaScript, Python, Go, SQL, PHP & Ruby
- **Frameworks** – Node.js, NestJS, Express, React, Vue, Laravel, Vite, Jest & tap
- **Datastores** – PostgreSQL, TimescaleDB, MySQL, MongoDB, Redis & BigQuery
- **Platform** – Kubernetes, FluxCD, Helm, Airflow, Docker, Terraform & OpenTofu
- **Cloud** – GCP (GKE, Cloud Run, Cloud SQL), AWS, Azure & OpenShift
- **Observability** – Grafana, VictoriaMetrics, Alloy, PromQL & SLOs
- **Security & Compliance** – SBOM, Dependency-Track, SSVC, OWASP ASVS, Auth0, Permify, ISO 27001, NIS2 & EU Cyber Resilience Act

## Experience

### Lead Software Engineer, Ampowr B.V.

February 2026 – Present

Ampowr is a Dutch battery energy storage company, running its own software across more than 100 customer sites.

- Accountable owner of two EU regulatory programmes: the Digital Battery Passport (EU Battery Regulation, due February 2027) and the Cyber Resilience Act, including vulnerability triage with SSVC and the Article 14 reporting process.
- Lead engineer for the cloud platform: site management APIs and UI, TimescaleDB, Airflow on GKE, and infrastructure as code with Terraform and OpenTofu.
- Introduced GitOps to Ampowr. Kubernetes workloads had no GitOps before; Airflow and the shared backoffice cluster now deploy through FluxCD.
- Built the open source governance programme: SBOMs for all deployed components, Dependency-Track, a licence approval playbook, and evidence mapped to ISO 27001 controls.
- Set engineering standards across the organisation: code owners on 60 repositories, secret and dependency scanning on 56, and a minimum standard for production components agreed by the team.
- Led incident response and introduced blameless post-mortems. Reworked SLOs and alerting so critical alerts are no longer lost in noise.
- Supported the migration of the customer fleet from OpenEMS to Nova, Ampowr's own energy management stack.
- Wrote the H2 2026 roadmap for Site Management and turned it into engineering goals for the team.
- Wrote the Software Department career framework and a mentoring roadmap, and took over team retros and sprint ceremonies.
- Started Innovation Days to build a learning culture. After a team survey, ran a two-day pilot in November 2026: roadmap sessions per domain to plan H1 2027, then an unconference and hackathon. Proposed regular innovation days for 2027 based on the result.
- Reviewed more than 250 pull requests in four months.

#### Highlights

- Recovered a TimescaleDB cluster close to a full disk without a long outage. A full background worker pool had stopped all maintenance jobs for over a year; fixing it freed about 13 TiB on each host.
- Prepared site management for its 2026 penetration test with a white-box review and an OWASP ASVS pass, then shipped around 15 authorisation and validation fixes before testing started.
- Found why customer dashboards were slow: short time ranges skipped the pre-aggregated data, so an 8 hour query was about 500 times slower than a 9 hour one.
- Selected and deployed Apache Airflow on GKE, with Cloud KMS, External Secrets, alerting and a chaos test to prove failures are reported.

### Staff Software Engineer, Snyk Ltd

October 2022 – January 2026

Snyk builds security tools for developers, helping companies use open source software safely.

- Worked across engineering groups to prioritise, plan and deliver work with clear business value.
- Wrote TypeScript and Go, shipped through CI/CD, and automated the infrastructure for our services and distributed applications.
- Did exploratory design and architecture work to support the growth of the platform.
- Improved API performance, reliability and usability, based on monitoring and analysis.
- Mentored and coached engineers across the group.
- Integrated our products with partner systems.
- Took part in the on-call rotation for production services.

#### Highlights

- Zero-day game day: a company-wide exercise simulating a zero-day vulnerability in one of our dependencies, and its wider effect on our customers.
- Supported engineers across the company with their career development.

### Interim Engineering Director, Snyk Ltd

October – December 2023

- Responsible for the security intelligence and data engineering teams behind the open source security products.
- Worked with the wider engineering leadership team to set the future direction of the group.
- Supported the engineering and product teams through a period of change.

## Previous Experience

### Senior Software Engineer, Snyk Ltd

January 2021 – October 2022

- Shaped the product and guided the team across several components and projects.
- Proposed design improvements with both short and long term benefits.
- Wrote code, built prototypes and designed testing strategies, delivering in small steps.
- Supported inclusion and growth through pairing, feedback and mentoring.
- Worked with Product and Design to turn requirements into working features.
- Kept the developer experience consistent across all Snyk products.

#### Highlights

- Added support for `critical` severity across the whole Snyk platform, working with Product and Design so the information was clear and actionable.

### Software Team Lead, Snyk Ltd

September 2019 – January 2021

- Gave team members regular feedback, mentoring and coaching.
- Hired the right people to help the team grow.
- Ran quarterly planning sessions for our distributed team.
- Worked with the product manager to plan and reach goals, communicate early, and set realistic expectations with stakeholders.
- Balanced feature delivery with ongoing technical investment.

#### Highlights

- Introduced an experiment-based way of working, so we could test and improve how people used and adopted our features.
- Led planning sessions at the annual all-hands and presented the results to an audience of 200.

### Developer, Snyk Ltd

October 2017 – September 2019

- Designed features with the product team based on user needs, and planned how to build them.
- Delivered a SaaS application in small steps through a full CI/CD workflow.
- Worked in a distributed team, communicating clearly and early.

#### Highlights

- Introduced Vue to start moving from a server-rendered application to client-side components, for more interactive features.
- Moved the end-to-end test suite from Nightwatch to Cypress, making it easier for developers to run and write tests locally.

### Technical Lead, Bravo Charlie Mike Hotel

January 2015 – October 2017

A design and branding agency delivering projects for international clients across many sectors.

- Led delivery of all digital projects, covering the full project life‑cycle and client relationships.
- Scoped and managed projects with clients so their systems were delivered on time.
- Joined the directors at new business pitches, contributing technical ideas that helped win work.
- Worked closely with designers on prototypes showing how their designs would work across devices.
- Wrote documentation and gave training at project handover.
- Set up feedback cycles with clients so larger projects could run in sprints.

Alongside client work I also:

- Built invoicing software for the company and introduced accounting software that automated most financial tasks.
- Maintained the studio's computers (mostly macOS).
- Introduced offsite backups to protect the company's data.

#### Highlights

- Worked with the Kings Cross estates team on a performance piece of fountains driven by GIF imagery, accompanying a string quartet in Granary Square. Part of the designjunction event, it drew over 25,000 visitors in one weekend.
- Introduced the team to new ways of working, such as weekly sprints and mobile-first, responsive design.

### Director, LA Code & Design Ltd

December 2012 – 2014

Worked as a full stack web developer on contract for several London design studios.

- Worked with designers from early prototyping and scoping through to completion, troubleshooting and handover.
- Gave in-office training to client teams at handover.

#### Highlights

- Worked with teams at several studios, which gave me experience of different ways of working.
- Had the flexibility to attend industry events in the UK and abroad.

### Developer, Signal Noise

September 2010 – November 2011

As the first hire at this data design agency, I worked directly with the design directors on web projects and physical prototypes.

### Sessional Lecturer, University of the Arts London & University for the Creative Arts

September 2010 – June 2012

I taught web technologies as a medium for editorial work on undergraduate and postgraduate courses. Each short course mixed introductory sessions with one-to-one workshops with students.

### Developer, Inventive & Co

Summer 2010

Worked with a senior developer to design and build a custom CMS for a production studio. It handled video uploads and transcoding for playback in a custom Flash media player.

## Volunteering

### Board Member, One Army Foundation

January 2024 – Present

### Maintainer, Community Platform for One Army Foundation

October 2021 – December 2023

## Interests

Away from the computer, I’m a keen cyclist and can often be found meandering around the Dutch polders looking for a hill to roll down. I enjoy longer endurance rides, the longest one to date being ~250km.

I’m also in the early stages of learning Dutch, maar het is een langzaam proces.

## Education

### University for the Creative Arts

September 2007 – June 2010

BA Hons - Graphic Design New Media 2:1

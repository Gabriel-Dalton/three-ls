# Evidence and measurement

The 3 Ls provide a way to act. They do not calculate a carbon footprint or certify a service as sustainable.

## Make the claim match the evidence

Distinguish four things:

| Type | Example | What to report |
| --- | --- | --- |
| Observation | A page transferred fewer bytes in a repeat test. | Tool, date, pages, device or connection conditions, and before/after results. |
| Measurement | A meter recorded electricity used by a device. | Equipment, duration, system boundary, and what the reading excludes. |
| Modelled estimate | A method estimates emissions from activity and assumptions. | Method and version, inputs, boundary, uncertainty, and source dates. |
| Unknown | A provider does not disclose the energy used by this service. | What you looked for and what is missing. |

A performance score is not an emissions measurement. A percentage reduction per page visit is not automatically the same percentage reduction for an organisation. More usage can also change the overall result.

## Be careful with familiar shortcuts

- **AI versus search:** avoid a universal energy multiplier. A comparison needs defined tasks, systems, boundaries, and current evidence.
- **Email and storage:** deleting a given number of messages does not prove a fixed electricity or carbon saving. Storage, replication, retention, and infrastructure behaviour matter. Preventing unwanted messages is a concrete change; quantify its environmental effect only with supporting evidence.
- **Water:** avoid a fixed amount per query without a method that accounts for location, cooling, and the boundary of the estimate.
- **Offsets:** report them separately from reductions in resource use or emissions.

Some figures in an earlier talk may be historical or depend on assumptions that do not fit today's tools. This repository keeps the framework usable without relying on those figures. When sharing a statistic, return to its original source and check its date, scope, and limitations.

## A useful reporting format

> We changed [specific thing] to achieve [purpose]. We observed [result] using [method] on [date] under [conditions]. This tells us [supported conclusion]. We have not measured [remaining unknown].

The [illustrative scenarios](examples/README.md) are fictional. The [Mittler Senior Technology case study](case-studies/mittler-senior-technology.md) describes a real project using published results and explains the limits of that record.

## Further reading

- [W3C Web Sustainability Guidelines, 24 September 2026 draft](https://www.w3.org/TR/2026/DNOTE-web-sustainability-guidelines-20260924/): practical guidance for digital services, including media, code, infrastructure, and organisational practices. This is a Group Note Draft and a work in progress.
- [Green Software Foundation: Software Carbon Intensity specification](https://sci.greensoftware.foundation/): a method for relating software emissions to a defined functional unit and system boundary.
- [Gabriel's TEDx talk](https://www.youtube.com/watch?v=9L3bjj3GkSI): the presentation in which the framework was introduced. Treat numerical claims as claims from that presentation, with their original context and date.

External resources inform the guidance; their inclusion does not imply endorsement of the 3 Ls. Links and document status checked on 8 October 2026.

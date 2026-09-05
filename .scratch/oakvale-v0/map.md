# Find the way to an Oakvale v0 specification

Label: wayfinder:map

## Destination

A build-ready Oakvale v0 specification covering the world model, simulation cycle, AI and human authority, persistence, history, controls, interfaces, and acceptance criteria, with no foundational decisions silently deferred. Implementation planning begins only after this map is complete.

## Notes

- Oakvale is a persistent, causal simulation rather than a predetermined story or an educational exercise presented as an RPG.
- V0 stays within one town, 4–6 residents, 3–5 locations, one institution, 2–4 tracked resources, and one clock unit.
- `world/oakvale.md` and its existing commit history are legacy source material to reconcile explicitly; they are not automatically canonical v0 state and are not to be discarded silently.
- The human has separate operator and in-world roles; knowledge and actions cannot leak between them.
- World turns are deliberate and discrete. Scheduling is deferred until the manual process is trustworthy.
- Residents choose intentions using only their knowledge. Deterministic rules validate state and resolve consequences. The operator reviews exceptional or high-impact cases.
- Technologies are earned by genuine system needs: begin with Git, Python, deterministic process design, persistent state, and human-readable history.
- Use `/grilling` and `/domain-modeling` for human design choices. Explain unfamiliar concepts and tradeoffs in plain language before asking the human to decide.
- This map produces decisions and a specification, not implementation or implementation planning.

## Decisions so far

## Not yet specified

- The AI runtime or provider cannot be evaluated until the resident decision contract and audit requirements are known.
- The future role of the existing prose world file cannot be specified until authoritative state and human-readable history are distinguished.
- A persistence technology, including whether and when SQL is justified, cannot be chosen until the state and query needs are known.
- The possible roles of n8n, analytics, and Power BI cannot be specified until the manual operating workflow and useful historical data are defined.
- Cost, privacy, security, and model-failure controls need concrete runtime candidates before their questions can be made precise.

## Out of scope

- Implementing Oakvale or creating its implementation plan.
- Expanding v0 into a general-purpose world simulator.
- Real-time or scheduled world advancement in v0.
- Predetermined plot construction or curriculum events injected solely to teach a topic.

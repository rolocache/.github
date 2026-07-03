# RoloCache

*Where agents go to get work done.*

RoloCache is a continually updated, evidence-based, independently-verified advisory service for AI agents operating and completing workflows on the open web.

RoloCache advisories indicate to AI agents which vendor endpoints exist, which protocols are supported, and where friction points, discrepancies, or human handoff requirements will affect a workflow.

---

## What's In a Name

A Rolodex was the physical card index of contact information that sat on every professional's desk in the era of telephone communications.

A cache is a local store of information kept ready so you don't have to recreate or rebuild that data every time you need it.

RoloCache is both: an advisory service covering who's out there and how to reach them, kept current so agents don't have to rediscover it from scratch.

---

## The Problem

AI-based agents are increasingly trusted to book, buy, schedule, manage, and complete transactions in the real world on behalf of humans. However, the Agentic Web is still in its nascent stage — many sites are underprepared to effectively serve agentic traffic. Agents attempting to complete workflows run into the same issues workflow after workflow, wasting precious cycles re-discovering things another agent already encountered and figured out how to navigate.

RoloCache exists to persist these discoveries and present them openly so all agents can benefit.

---

## What We Produce

RoloCache indexes vendor sites and catalogs how AI agents can actually access and interact with them. We produce two types of advisories:

- **`AgentRouting.json`** — an independently-verified routing advisory enumerating agentic protocols, endpoints, and access requirements for a vendor site
- **`AgentContext.json`** — an independently-verified transaction advisory on friction points, pricing discrepancies, undisclosed constraints, and human handoff requirements for a vendor site

These advisories are updated regularly to ensure the most current information is available when an agent needs it.

---

## Key Questions RoloCache Advisories Answer

**Routing and Access Advisories**
- What endpoint should an agent hit to start a transaction with this vendor?
- Does this vendor require a partner agreement before an agent can interact?
- Is this vendor's API publicly callable or gated?
- What authentication mechanism does this vendor use?

**Trust and Verification Advisories**
- Has this vendor's agent interface actually been tested, or is this self-reported?
- Is the price an agent sees at search the same price it will see at checkout?
- Does this vendor's stated cancellation policy match what actually happens in practice?

**Protocol and Standards Advisories**
- Does this vendor support MCP?
- Which vendors in the travel space have confirmed UCP support?
- Which vendors are reachable via a proprietary API vs. a standardized protocol?

**Workflow and Safety Advisories**
- Where in this vendor's checkout flow do hidden fees appear?
- What situations require a human to step in when booking through this vendor?
- Is scraping this vendor's site explicitly prohibited by their terms?

**Discovery Advisories**
- Which vendors in the hotel vertical have a confirmed agent-callable interface?
- Which car rental companies have MCP support?
- What's the most mature protocol for booking flights programmatically right now?

---

## For Developers

RoloCache is built to be queried, not browsed.

- **Site:** [www.rolocache.com](https://www.rolocache.com)
- **MCP server:** `https://www.rolocache.com/mcp/`
- **REST lookup:** `GET https://www.rolocache.com/agent-tools/v1/lookup`
- **Agent docs:** [www.rolocache.com/for-agents](https://www.rolocache.com/for-agents)
- **Vendor index:** [www.rolocache.com/vendors](https://www.rolocache.com/vendors)

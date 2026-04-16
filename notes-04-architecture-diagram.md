# Architecture Diagram

## Top: Gaps

A row of boxes representing the queue of gaps.

## Left Side: Orchestration

- Research
- Testing
- Decomposing
- Alignment management (clean, delete, etc.)

**Terminal → View**

## Middle: Drones

Multiple drone instances (ovals) that receive tasks from the gaps queue and interact bidirectionally with the Collective Mind.

## Bottom: Collective Mind

Central ellipse — the shared knowledge store.

Connected components hanging below:

- **Skills**
- **Tools** *(crossed out)* → **Tool registry** (starts empty, parsed over time)
- **Findings**
- **User uploads**
- **Model registry**
- **Gaps** (feeds into Collective Mind)

## User

Stick figure → **goal** (user provides the initial goal to the system)

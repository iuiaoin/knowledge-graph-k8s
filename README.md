# Kubernetes Concepts — Knowledge Map

An interactive concept map of the Kubernetes [Concepts documentation](https://kubernetes.io/docs/concepts/),
distilled from the `docs/` snapshot (176 pages, ~283K words) into 39 concepts across 8 groups.

## Viewing

Open [`knowledge-graph/k8s-concepts-map.html`](knowledge-graph/k8s-concepts-map.html) in any browser —
it is fully self-contained (no server or network needed). Node links open the published pages on kubernetes.io.

Viewer controls: `/` to search, legend chips to show/hide groups, edge-label and list-view toggles,
light/dark theme, click a node for its summary and doc link, drag to pin, double-click to release.

## Contents

| Path | What it is |
|---|---|
| `docs/` | Source snapshot of the Kubernetes Concepts docs (markdown) |
| `knowledge-graph/graph.json` | The designed graph — nodes, edges, groups |
| `knowledge-graph/survey.json` | Full page inventory generated from `docs/` |
| `knowledge-graph/k8s-concepts-map.html` | The interactive map (the deliverable) |

## Build

Built with the [`knowledge-graph`](https://github.com/iuiaoin/agent-skills#knowledge-graph) skill.

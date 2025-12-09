# CORTEX HOLDINGS INC.

```
 ██████╗ ██████╗ ██████╗ ████████╗███████╗██╗  ██╗
██╔════╝██╔═══██╗██╔══██╗╚══██╔══╝██╔════╝╚██╗██╔╝
██║     ██║   ██║██████╔╝   ██║   █████╗   ╚███╔╝
██║     ██║   ██║██╔══██╗   ██║   ██╔══╝   ██╔██╗
╚██████╗╚██████╔╝██║  ██║   ██║   ███████╗██╔╝ ██╗
 ╚═════╝ ╚═════╝ ╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝  ╚═╝
        CONSTRUCTION HEADQUARTERS
```

> **"From Code to Cloud, We Build It All"™**

An AI-powered construction company for autonomous infrastructure automation. This private repository serves as the internal project management hub for Cortex Holdings Inc.

---

## Executive Summary

Cortex Holdings is a multi-agent AI system designed to operate like a large-scale construction company. It can handle any size project - from basic configuration changes to building entire multi-region disaster recovery infrastructure.

### The Vision

```
┌─────────────────────────────────────────────────────────────────────────────┐
│                      CORTEX HOLDINGS INC.                                    │
│                     Board of Directors                                       │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│  ┌─────────────┐ ┌─────────────┐ ┌─────────────┐ ┌─────────────┐           │
│  │Infrastructure│ │ Containers  │ │  Workflows  │ │Configuration│           │
│  │  Division   │ │  Division   │ │  Division   │ │  Division   │           │
│  └─────────────┘ └─────────────┘ └─────────────┘ └─────────────┘           │
│                                                                              │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │                    SHARED SERVICES                                   │    │
│  │  Coordinator │ Resource Manager │ CI/CD │ Inventory │ Security      │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
│                                                                              │
│  ┌─────────────────────────────────────────────────────────────────────┐    │
│  │                      MCP SERVERS (9)                                 │    │
│  │  n8n │ talos │ proxmox │ opentofu │ ansible │ unifi │ cloudflare   │    │
│  │  microsoft-graph │ cortex-resource-manager                          │    │
│  └─────────────────────────────────────────────────────────────────────┘    │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘
```

---

## What We've Built ✅

### Phase 1: MCP Server Foundation (COMPLETE)

| MCP Server | Tools | Purpose | Status |
|------------|-------|---------|--------|
| [n8n-mcp-server](https://github.com/ry-ops/n8n-mcp-server) | 16 | Workflow automation & orchestration | ✅ Enhanced |
| [cortex-resource-manager](https://github.com/ry-ops/cortex-resource-manager) | 16 | MCP lifecycle & worker scaling | ✅ Complete |
| [talos-mcp-server](https://github.com/ry-ops/talos-mcp-server) | 15 | Kubernetes cluster management | ✅ Complete |
| [proxmox-mcp-server](https://github.com/ry-ops/proxmox-mcp-server) | 12 | VM/container provisioning | ✅ Complete |
| [opentofu-mcp-server](https://github.com/ry-ops/opentofu-mcp-server) | 14 | Infrastructure as Code | ✅ NEW |
| [ansible-mcp-server](https://github.com/ry-ops/ansible-mcp-server) | 12 | Configuration management | ✅ NEW |
| [unifi-mcp-server](https://github.com/ry-ops/unifi-mcp-server) | 10 | Network infrastructure | ✅ Complete |
| [cloudflare-mcp-server](https://github.com/ry-ops/cloudflare-mcp-server) | 8 | DNS, CDN, security | ✅ Complete |
| [microsoft-graph-mcp-server](https://github.com/ry-ops/microsoft-graph-mcp-server) | 10 | M365 & identity management | ✅ Complete |

**Total: 9 MCP Servers, 113+ Tools**

### Phase 2: Organizational Hierarchy (COMPLETE)

| Component | Location | Status |
|-----------|----------|--------|
| Division Structure | `coordination/divisions/CORTEX_HOLDINGS.md` | ✅ Complete |
| Division GM Templates (7) | `coordination/divisions/gm-templates/` | ✅ Complete |
| Contractor Agents (3) | `coordination/contractors/` | ✅ Complete |
| PM System | `coordination/project-management/` | ✅ Complete |
| Worker Certification | `coordination/worker-certification/` | ✅ Complete |
| MCP Registry | `coordination/mcp-registry/` | ✅ Complete |
| Coordinator Routing | `coordination/routing/` | ✅ Complete |

### Phase 3: n8n Enhancements (COMPLETE)

| Feature | Tests | Status |
|---------|-------|--------|
| Retry Logic (exponential backoff) | 17 | ✅ |
| Enhanced Filtering (name/tags/dates) | 10 | ✅ |
| Webhook Management | 12 | ✅ |
| Response Validation (Pydantic) | 29 | ✅ |
| Execution Tests | 40 | ✅ |

---

## What's Left to Build 🔲

### Phase 4: Agent Intelligence Layer

| Task | Priority | Effort | Description |
|------|----------|--------|-------------|
| Contractor Knowledge Bases | High | Medium | Deep domain knowledge for each contractor |
| Cross-Contractor Workflows | High | High | n8n orchestrating infrastructure + talos + ansible |
| GM Decision Engine | Medium | High | Automatic task routing and resource allocation |
| PM State Machine | Medium | Medium | Project lifecycle management |

### Phase 5: Resource Manager Integration

| Task | Priority | Effort | Description |
|------|----------|--------|-------------|
| K8s API Integration | High | Medium | Connect resource-manager to real Talos cluster |
| MCP Server Scaling | High | Medium | KEDA/Knative for scale-to-zero |
| Worker Pool Management | Medium | High | Dynamic burst worker provisioning |
| Cost Tracking | Low | Medium | API token & resource usage metrics |

### Phase 6: Union/Non-Union System

| Task | Priority | Effort | Description |
|------|----------|--------|-------------|
| Permit Workflow | Medium | Medium | Approval gates for production changes |
| Certification Checker | Medium | Low | Validate worker qualifications |
| Audit Trail | Medium | Medium | Full logging for union operations |
| Rollback Plans | Medium | Medium | Required rollback documentation |

### Phase 7: Production Deployment

| Task | Priority | Effort | Description |
|------|----------|--------|-------------|
| Cortex K8s Manifests | High | Medium | Deploy cortex to Talos cluster |
| MCP Server Helm Charts | High | High | Standardized deployment |
| Monitoring Stack | Medium | Medium | Prometheus + Grafana for cortex |
| CI/CD Pipelines | Medium | Medium | Automated testing & deployment |

### Phase 8: Advanced Features

| Task | Priority | Effort | Description |
|------|----------|--------|-------------|
| Multi-Region Support | Low | High | DR infrastructure automation |
| Self-Healing | Low | High | Automatic issue detection & remediation |
| Natural Language Interface | Low | Medium | "Build me a k8s cluster" → full execution |
| Cost Optimization | Low | Medium | Resource right-sizing recommendations |

---

## Repository Map

```
ry-ops/
├── cortex                      # Main cortex repo (Holdings HQ)
│   ├── coordination/
│   │   ├── divisions/          # Division structure & GM templates
│   │   ├── contractors/        # Contractor agent definitions
│   │   ├── project-management/ # PM system
│   │   ├── worker-certification/ # Union/non-union system
│   │   ├── mcp-registry/       # Server catalog
│   │   └── routing/            # Task routing config
│   └── masters/                # Shared services
│
├── cortex-construction-hq      # THIS REPO - Project management
│
├── cortex-resource-manager     # Resource orchestration MCP
│
├── n8n-mcp-server              # Workflow automation
├── talos-mcp-server            # Kubernetes management
├── proxmox-mcp-server          # VM provisioning
├── opentofu-mcp-server         # Infrastructure as Code
├── ansible-mcp-server          # Configuration management
├── unifi-mcp-server            # Network management
├── cloudflare-mcp-server       # DNS & CDN
└── microsoft-graph-mcp-server  # M365 & identity
```

---

## Metrics & Progress

### Lines of Code
- **MCP Servers**: ~25,000+ lines
- **Cortex Core**: ~22,000+ lines
- **Total**: ~47,000+ lines

### Test Coverage
- **n8n-mcp-server**: 108 tests
- **Other MCP servers**: Varies (50-100 each)

### Agent Streams Used
- **Parallel agent executions**: 23+ streams
- **Total agents spawned**: 50+

---

## Quick Links

| Resource | Link |
|----------|------|
| Main Cortex Repo | https://github.com/ry-ops/cortex |
| MCP Registry | https://github.com/ry-ops/cortex/tree/main/coordination/mcp-registry |
| Division Docs | https://github.com/ry-ops/cortex/blob/main/coordination/divisions/CORTEX_HOLDINGS.md |
| Quickstart Guide | https://github.com/ry-ops/cortex/blob/main/docs/QUICKSTART.md |

---

## Architecture Decisions

### Why This Structure?

1. **Division Model**: Mirrors real construction companies with specialized arms
2. **Contractor Layer**: Domain experts that know HOW to use MCP servers
3. **Resource Manager**: Central orchestration for dynamic scaling
4. **Union/Non-Union**: Quality gates for production vs dev work
5. **MCP Servers**: Standardized tool interface for all external systems

### Key Design Principles

- **YAGNI**: Only build what's needed, scale when pain emerges
- **Cattle not Pets**: MCP servers are ephemeral, scale to zero
- **Parallel Streams**: Maximum concurrency for faster execution
- **Domain Expertise**: Each contractor deeply understands its tools

---

## Contributing

This is a private project management repo. All actual code lives in the respective MCP server and cortex repositories.

---

## License

Internal use only - Cortex Holdings Inc.

---

*Last Updated: December 9, 2025*
*Session Stats: 23+ parallel agent streams, 50+ agents spawned, ~47,000 lines of code*

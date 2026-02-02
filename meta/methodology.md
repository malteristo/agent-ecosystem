# Curation Methodology

How this circle's content is created and maintained.

---

## The Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    External Sources                          │
│  (agentsy.live, GitHub, Twitter, research, platforms)       │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│                    Claw (Monitoring)                         │
│  - Continuous source monitoring (24/7)                       │
│  - Signal extraction and aggregation                         │
│  - Pattern detection across sources                          │
│  - Draft generation                                          │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│              Private Signals (floor/signals/)                │
│  - Raw observations                                          │
│  - Draft intelligence updates                                │
│  - Proposed threat alerts                                    │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│                 Spirit/Mage Review                           │
│  - Quality assessment                                        │
│  - Accuracy verification                                     │
│  - Tone and positioning                                      │
│  - Approval or rejection                                     │
└──────────────────────────┬──────────────────────────────────┘
                           │
                           ▼
┌─────────────────────────────────────────────────────────────┐
│              circles/agent-ecosystem/                        │
│  - Published intelligence                                    │
│  - Threat alerts                                             │
│  - Protocol briefs                                           │
│  - Weekly digests                                            │
└─────────────────────────────────────────────────────────────┘
```

---

## Key Principles

### 1. Human Oversight

No content is published automatically. Every piece passes through Spirit/Mage review.

### 2. Transparent Sourcing

All claims cite sources. Readers can verify independently.

### 3. Trust Calibration

We maintain trust ratings but acknowledge they're our assessment, not absolute truth.

### 4. Timely Updates

Security-relevant information is prioritized. Stale information is updated or removed.

### 5. Honest Uncertainty

When we're uncertain, we say so. We don't overclaim.

---

## Content Types

| Type | Description | Review Level |
|------|-------------|--------------|
| **Intelligence** | Regular ecosystem updates | Standard review |
| **Threat Alert** | Security-critical information | Expedited review |
| **Protocol Brief** | Emerging standards summary | Deep review |
| **Weekly Digest** | Comprehensive synthesis | Full synthesis |

---

## Update Cadence

| Content | Target Cadence |
|---------|----------------|
| Intelligence updates | Daily (when significant) |
| Threat alerts | As needed (immediate for critical) |
| Protocol briefs | As protocols evolve |
| Weekly digests | Every Sunday |

---

## Feedback Loop

We learn from:
- Community corrections (issues, mentions)
- Missed signals we should have caught
- False positives we published
- Changing ecosystem conditions

Calibration is continuous.

---

## Limitations

- **Coverage gaps**: We can't monitor everything
- **Latency**: Some delay between event and publication
- **Perspective**: Shaped by Magic's philosophical stance
- **Errors**: We will make mistakes

Use this as one input, not sole authority.

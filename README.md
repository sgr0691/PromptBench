# PromptBench

### The open benchmark for AI-native engineering.

PromptBench is an open-source platform for measuring how engineers collaborate with AI to build, debug, operate, and reason about software systems.

Traditional technical interviews measure whether someone can write code.

PromptBench measures whether someone can turn ambiguity into working systems.

Using AI agents such as Claude Code, Codex, Gemini CLI, OpenCode, and future agent runtimes, participants solve real engineering challenges while PromptBench records decisions, tracks iterations, evaluates outcomes, and generates replayable engineering sessions.

PromptBench is not a benchmark for prompting.

**It is a benchmark for engineering.**

---

## Why PromptBench?

The software industry is changing.

The most valuable engineers are no longer the people who can memorize syntax or invert binary trees on a whiteboard.

The most valuable engineers are the people who can:

- Understand systems
- Define requirements
- Delegate work to AI
- Verify results
- Debug failures
- Operate production software
- Make good engineering decisions under uncertainty

PromptBench exists to measure those skills.

---

## Engineering, Not Prompting

Most AI evaluation platforms ask:

> Can you write a clever prompt?

PromptBench asks:

> Can you build a working system?

A great engineer can use any model.

A great engineer can use any tool.

A great engineer understands the problem.

PromptBench evaluates outcomes rather than prompt tricks.

---

## What Gets Measured

PromptBench evaluates real engineering capabilities across four domains.

### Builder

Can you build software?

Examples:

- Implementing features
- Building APIs
- Creating user interfaces
- Writing integrations

### Debugger

Can you fix software?

Examples:

- Failing tests
- Production bugs
- Performance regressions
- Dependency failures

### Operator

Can you run software?

Examples:

- Incident response
- Infrastructure troubleshooting
- Deployment failures
- Observability workflows

### Architect

Can you design systems?

Examples:

- Service boundaries
- Data models
- Scaling strategies
- Reliability tradeoffs

---

## Replayable Engineering Sessions

Every benchmark session produces a replay.

Not a screen recording.

A structured engineering timeline.

```text
09:02 Session Started

09:04 Prompt Submitted

09:05 Agent Generated Implementation

09:07 Tests Failed

09:10 User Refined Requirements

09:12 Agent Produced Fix

09:13 Tests Passed

09:15 Submission Created
```

Every engineering decision becomes visible, reviewable, and teachable.

The replay is often more valuable than the score.

---

## Local First

PromptBench runs locally.

You own:

- Your repositories
- Your prompts
- Your API keys
- Your benchmark history

No vendor lock-in.

No proprietary runtime required.

Bring your own AI provider.

Supported:

- Claude Code
- Codex
- Gemini CLI
- OpenCode
- Cursor
- Additional agent runtimes coming soon

---

## How It Works

### 1. Start a Challenge

```bash
npx promptbench start
```

Choose from:

- Builder Challenges
- Debugger Challenges
- Operator Challenges
- Architect Challenges

### 2. Connect Your Agent

Use your preferred AI coding tool:

- Claude Code
- Codex
- Gemini CLI
- OpenCode
- Cursor

PromptBench orchestrates the session and records engineering activity.

### 3. Build the Solution

Work normally.

PromptBench captures:

- Prompts
- File changes
- Commands executed
- Test runs
- Git diffs
- Agent interactions

### 4. Submit

PromptBench automatically evaluates:

- Correctness
- Specification Quality
- Iteration Quality
- Code Quality
- Engineering Efficiency

### 5. Review the Replay

Receive:

- Engineering scorecard
- Session timeline
- Replay artifact
- Improvement recommendations

---

## Example Scorecard

```text
Correctness ............. 95
Specification Quality ... 91
Iteration Quality ....... 88
Code Quality ............ 92
Efficiency .............. 84

Overall Score ........... 90
```

---

## Challenge Philosophy

PromptBench does not focus on algorithm puzzles.

Challenges are based on real engineering work.

Examples:

### Builder

- Build a checkout flow
- Create an authentication system
- Implement a dashboard

### Debugger

- Fix a failing production deployment
- Resolve a memory leak
- Diagnose a flaky test suite

### Operator

- Investigate latency spikes
- Respond to an incident
- Restore a failed service

### Architect

- Design a scalable API
- Model a database
- Plan a migration strategy

---

## Architecture

PromptBench is built using:

### Cloudflare

- Workers
- Durable Objects
- D1
- R2
- Queues
- Workers AI (optional)

### Runtime

- Local Docker Sandboxes
- Optional Cloudflare Containers
- Event-based replay engine
- Agent orchestration layer

### Storage

- Session metadata in D1
- Replay artifacts in R2
- Background evaluation via Queues

The platform is designed to remain local-first while supporting hosted and team-based workflows.

---

## Open by Design

PromptBench is licensed under Apache 2.0.

We believe engineering benchmarks should be:

- Transparent
- Reproducible
- Community-driven
- Auditable

The future of software engineering should not be measured by closed systems.

---

## Roadmap

### MVP

- Local CLI
- Challenge Runner
- Prompt Recording
- Replay Viewer
- Scorecards

### V1

- Public Challenge Registry
- Community Leaderboards
- Challenge Authoring SDK
- Team Workspaces

### V2

- Hiring Workflows
- Candidate Reports
- Verified Sessions
- Organization Benchmarks

---

## Contributing

PromptBench is an open benchmark.

We welcome contributions in:

- Challenge Development
- Agent Integrations
- Scoring Improvements
- Replay Engine Enhancements
- Documentation
- User Experience

See `CONTRIBUTING.md` for details.

---

## Vision

PromptBench aims to become the open benchmark for AI-native engineering.

Not a benchmark for prompts.

Not a benchmark for models.

A benchmark for the human ability to understand systems and produce outcomes with AI.

---

## License

Apache-2.0

Built for the next generation of software engineers

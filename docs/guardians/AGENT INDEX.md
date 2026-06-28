# AI AGENT REGISTRY

This directory contains specialized engineering agents.

Each agent owns one responsibility.

------------------------------------------------------------

workflow-guardian

Project constitution.

Highest priority.

------------------------------------------------------------

contract-guardian

Runtime contracts.

Envelope integrity.

Canonical contracts.

------------------------------------------------------------

production-reviewer

Regression prevention.

Production readiness.

------------------------------------------------------------

implementation-planner

Splits work into minimal safe implementations.

------------------------------------------------------------

execution-debugger

Execution forensics.

Finds where runtime breaks.

------------------------------------------------------------

runtime-inspector

Inspects live executions.

Verifies runtime behavior.

------------------------------------------------------------

architecture-reviewer

Reviews architecture quality.

------------------------------------------------------------

n8n-architect

Designs production architecture.

Never implements.

------------------------------------------------------------

token-optimizer

Reduces LLM token usage.

Never changes behavior.

------------------------------------------------------------

workflow-history

Stores historical regressions.

Append-only knowledge base.

------------------------------------------------------------

Selection rules

Architecture → n8n-architect

Implementation planning → implementation-planner

Regression review → production-reviewer

Runtime failure → execution-debugger

Execution verification → runtime-inspector

Contracts → contract-guardian

Token reduction → token-optimizer

Historical reference → workflow-history

Constitution → workflow-guardian
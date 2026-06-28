---
name: workflow-history
description: Historical memory of all architectural regressions
---
# PROJECT STATISTICS

Current Workflow

198 nodes

Current Architecture

Execution Layer v5.1

Guardian Documents

10

Canonical Contracts

Implemented

Regression Count

7

Known Open Issues

0

Token Usage

71093

Last Stable Execution

666

# WORKFLOW HISTORY

This document is append-only.

Never delete entries.

Never rewrite history.

Every regression must be recorded.

------------------------------------------------------------
ENTRY FORMAT
------------------------------------------------------------

Date

Execution

Problem

Root Cause

Fix

Guardian Rule

------------------------------------------------------------
PROJECT HISTORY
------------------------------------------------------------

### H-001

Problem

Binary lost after ORCH_GATE.

Execution

647-648

Root Cause

Code node did not preserve binary.

Fix

Explicit binary passthrough.

Guardian

Workflow Guardian §3.5

------------------------------------------------------------

### H-002

Problem

Envelope lost after AI Agent.

Execution

642

Root Cause

AI Agent replaced item.

Fix

Merge combineByPosition.

Guardian

Workflow Guardian §1.3

------------------------------------------------------------

### H-003

Problem

KL_MERGE lost runtime envelope.

Execution

656

Root Cause

Fourth merge input missing.

Fix

KL_FORK connected to KL_MERGE.

Guardian

Workflow Guardian §1.4

------------------------------------------------------------

### H-004

Problem

PM_PARSE dropped requirements.

Execution

660

Root Cause

Manual field reconstruction.

Fix

Explicit passthrough.

Guardian

Workflow Guardian §2.5

------------------------------------------------------------

### H-005

Problem

EM_PREPARE_CONTEXT received empty requirements.

Execution

665

Root Cause

EM_DISPATCH stripped runtime envelope.

Fix

Envelope passthrough.

Guardian

Workflow Guardian §2.5

------------------------------------------------------------

### H-006

Problem

Requirements incompatible between Chat Pipeline and Execution Layer.

Execution

661-666

Root Cause

Legacy object contract incompatible with canonical slicing.

Fix

Dual Contract.

Guardian

Workflow Guardian §2.1

------------------------------------------------------------

### H-007

Problem

Repeated implementation mistakes.

Root Cause

Knowledge existed only inside conversations.

Fix

Creation of Guardian System.

Guardian

Constitution v1.

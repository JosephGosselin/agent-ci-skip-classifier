# Methodology

## Overview
Two parts: an empirical study of agent vs. human CI behaviour (RQ1–RQ2),
and a classifier + advise-only GitHub Action (RQ3–RQ4).
[workflow diagram]

## Data
- Agent data: AIDev (curated 33,596-PR subset, repos >100 stars), AgentPack (stratified sample)
- Human baseline: PRs from the same repositories and time window
- CI data: workflow runs and workflow files from the GitHub REST API
- Only repositories using GitHub Actions are included

## Attribution
How commits are identified as agent, human, mixed, or bot.

## Cleaning
What is removed and why (merge commits, bots, CI-config changes, small repos).

## Labelling
- Did CI run? (triggered / skipped, and the skip mechanism)
- Was CI needed? (rules for an unnecessary run)
- Uncertain cases and how they are reported
- Manual label check

## Features
Set A (from prior CI-skip work) and Set B (agent behaviour), as a table.

## Model
Decision tree, class weighting, chronological train/test split with tasks kept whole.

## Analysis
Statistical tests for agent vs. human comparisons.

## Evaluation
Metrics, baselines, feature ablation, historical replay, advise-only trial.

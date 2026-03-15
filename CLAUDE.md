# Tech Interview Prep: Ticketing System Simulation

## Assignment Context
- Course: AD311 Intermediate Application Development 1
- Task: Implement a queue to manage a ticketing system where users take a number and wait for their turn to be served
- Scenario: Simulate a service center where customers take a number and wait for their turn using a queue

## Problem Summary
Implement a ticketing system that:
- Defines a `Ticket` class with at least ticket number and timestamp
- Simulates customer arrivals by generating ticket objects and enqueuing them
- Dequeues and "serves" tickets by displaying their details
- Introduces timing where tickets are generated at random intervals and serving time may vary
- (Allowed) Separate ticket generation and processing into two distinct phases

## Deliverables Required
- Solution in `solution.py`
- ASCII diagrams/flowcharts of the approach
- Clarifying questions documented
- Pytest unit tests: 3+ normal cases, 3+ edge cases
- Time and space complexity analysis
- Optimized solution with trade-off explanation

## Workflow (from parent CLAUDE.md)
- Generate naive solution first, then optimize
- Analyze time/space complexity for both versions
- Create pytest unit tests (3+ normal, 3+ edge cases)
- Create simple ASCII diagrams for whiteboard explanation

## Style (from parent CLAUDE.md)
- Use Pythonic idioms
- Include docstrings with complexity analysis

## Constraints
- Must be presentable as a live coding interview (talk through decisions)
- Communicate clearly throughout - explain why you make each decision
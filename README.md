# Lab 7: Fuzz Testing for Input Validation Bugs

## Objective
Explore property-based fuzz testing as a security and quality assurance technique by identifying and fixing input validation bugs in `pizza_order.py` using Python's **Hypothesis** and **pytest** libraries[cite: 1, 3, 7].

## Repository Structure

| File | Description |
|------|-------------|
| `pizza_order.py` | Main pizza ordering application hardened against malformed and edge-case inputs[cite: 4, 7] |
| `test_pizza_order.py` | Property-based fuzz test suite written using Hypothesis[cite: 1, 7, 8] |

## Prerequisites & Setup

1. **Install dependencies:**
   ```bash
   pip install hypothesis pytest

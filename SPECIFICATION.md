# USD2 Flywheel Specification

## Overview

This document defines the formal specification for the USD2 flywheel system.

USD2 is a second-order value recycling layer derived from USD1 economic activity.
It does not custody, wrap, or modify USD1.

USD2 issuance is strictly a function of observed USD1 usage.

## Definitions

USD1 Volume (V):
Measurable economic activity involving USD1 within the execution domain.

Recycling Rate (R):
Deterministic coefficient applied to USD1 volume.

USD2 Issuance (I):
Quantity of USD2 produced per accounting interval.

## Core Equation

I = f(V, R)

If V = 0, then I = 0.

## Determinism

Given identical inputs, the system produces identical outputs.
No discretionary control exists.

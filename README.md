# Temporal Cut-Point Sampling

A project page about sampling synthetic decision cut-points so non-event cases have realistic observation windows.

## Project Website

[View Project Site](https://mah-trigui.github.io/temporal-cutpoint-sampling/)

## Overview

In this support escalation project, positive cases naturally stop at the escalation moment.

Negative cases do not.

If non-events keep their full history, the model sees more future information for the negative class than for the positive class.

## Core Idea

Synthetic decision cut-points were sampled from the empirical escalation-time distribution and applied to non-event cases, so both classes were observed through comparable partial timelines.

## Architecture

![Architecture](images/architecture.jpg)

## Key Takeaway

**Negative examples should not get more timeline than positive ones.**

## Public Scope

This repository shares the timeline-design principle, selected code logic, and project presentation only.

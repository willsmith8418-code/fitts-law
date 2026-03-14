# Fitts' Law Interactive Explorer

An interactive explainer for Fitts' Law — a foundational principle in human-computer interaction that predicts how long it takes to move a pointer and click a target.

## What it shows

Fitts' Law states that movement time (MT) is a function of the distance to a target (D) and the target's width (W):

**MT = a + b · log₂(2D / W)**

Targets that are far away and small take longer to acquire. Targets that are close and large are faster.

## Features

- Sliders to adjust distance and target width in real time
- Live index of difficulty, movement time, and D/W ratio
- Visual arena showing cursor and target positions
- Chart comparing how varying D vs. varying W affects movement time

## How to use

Open `fitts_law.html` in any browser, or view the live demo below.

## Live demo

[View it here](https://willsmith8418.github.io/fitts-law/fitts_law.html)

## Background

Fitts' Law was introduced by psychologist Paul Fitts in 1954 and remains one of the most cited models in UX and interface design. It underpins decisions like button sizing, menu placement, and touch target guidelines.

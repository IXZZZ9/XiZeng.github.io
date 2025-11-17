---
layout: single
title: "Research"
permalink: /research/
author_profile: true
---

My research addresses the fundamental challenge of **catastrophic forgetting** in modern AI systems—how neural networks lose previously learned knowledge when acquiring new capabilities. This problem is pervasive across large language models, vision systems, and reinforcement learning agents, limiting their deployment in dynamic real-world environments.

## Core Research Vision

I aim to develop principled approaches enabling AI systems to **learn continuously throughout their lifetime**, accumulating knowledge and capabilities while preserving what they have already learned. My work bridges theoretical understanding of gradient flow dynamics with practical algorithmic innovations for large-scale systems.

## Research Areas

### Continual Learning and Gradient Flow Analysis

**Key Insight**: Catastrophic forgetting is fundamentally a gradient geometry problem. When neural networks learn sequential tasks, gradient updates create weight perturbations that destroy previously learned decision boundaries.

**Current Focus**:
- Characterizing gradient flow dynamics in large-scale architectures during continual learning
- Developing mathematical frameworks to predict parameter vulnerability to forgetting
- Designing scalable algorithms that leverage gradient flow analysis for selective parameter updates

**Project**: **ActionRes Framework**
- First systematic connection between delta actions and catastrophic forgetting dynamics
- Investigates knowledge accessibility versus destruction during sequential learning
- Explores how residual architectures preserve learned representations

### Efficient Training Methods for Deep Learning

**Project**: **GradES (Gradient-Based Early Stopping)**
- Co-first author on submission to ICLR 2026
- Achieves significant speedups in transformer training through intelligent gradient monitoring
- Demonstrates how gradient analysis optimizes both efficiency and knowledge preservation
- Released open-source implementation on GitHub, PyPI, and Hugging Face

### Medical AI and Interpretability

**Atherosclerosis Detection System**
- Developed predictive models using multivariate health metrics
- Applied rigorous statistical validation for clinical reliability
- Addressed challenges of class imbalance and feature correlation in medical data

**Interpretable Silent Speech Recognition**
- Pioneered electrode mapping framework using Deep Forest's MDI interpretability
- Demonstrated performance maintenance with reduced electrode sets
- Achieved significant cost reduction for practical deployment

### Low-Rank Adaptation for Efficient Model Deployment

**MediaPipe Enhancement with LoRA**
- Adapted Google MediaPipe's MLP layers for robust keypoint detection under occlusion
- Achieved effective downstream task adaptation with minimal training overhead
- Optimized for on-device deployment with compact model sizes

## Future Research Directions

### Large Language Models
- Developing continual learning frameworks enabling knowledge accumulation without forgetting
- Investigating gradient flow patterns across transformer layers during sequential learning
- Exploring parameter-efficient methods (LoRA, adapters) that isolate new knowledge

### Deep Reinforcement Learning
- Multi-agent systems maintaining coordination while adapting to new environments
- LLM-guided RL with preserved world knowledge across task transitions
- Gradient flow analysis in actor-critic architectures

### Vision-Language Models
- Addressing multimodal alignment challenges during continual learning
- Preserving cross-modal understanding while acquiring domain-specific capabilities

## Research Philosophy

I believe in conducting research that bridges the gap between theoretical understanding and practical impact. Each project I undertake aims to:

1. **Identify fundamental mechanisms** underlying AI limitations
2. **Develop principled solutions** grounded in mathematical understanding
3. **Validate through extensive experimentation** across diverse domains
4. **Deploy as open-source tools** for community benefit

My goal is to contribute to building truly intelligent, adaptive systems that can learn and evolve throughout their operational lifetime, bringing us closer to artificial general intelligence.
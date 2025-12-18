# Complexity

- A library for state-of-the-art `Markov Chain Monte Carlo (MCMC)` simulations applied to `AI` `LLM` streaming responses.

- Evaluate the financial-value of any given `prompt-response` pair.
- Designed to learn temporally or improve in accuracy with respect to (w.r.t.) time.
- [Black-Scholes warning](https://en.wikipedia.org/wiki/Black%E2%80%93Scholes_model) 🦆

- *Install the Library, via the instructions below to learn more and apply the model to your own LLM streaming...*

![alt text](/assets/Stable%20Diffusion%20Prediction.webp "Complexity, computed via Replicate | stability-ai/stable-diffusion-3.5-large ")
> ___Complexity___: computed via [Replicate | stability-ai/stable-diffusion-3.5-large.](https://replicate.com/stability-ai/stable-diffusion-3.5-large)

---

### Installation Instructions

To install dependencies:

```bash
bun install
```

To run:

```bash
bun run index.ts
```

This project was created using `bun init` in bun v1.2.16. [Bun](https://bun.sh) is a fast all-in-one JavaScript runtime.


## What is a Markov Chain Monte Carlo sim.?

### Basic History and Motivation

Written in the mid 20th-century, the [Markov Chain Monte Carlo (MCMC)](https://en.wikipedia.org/wiki/Markov_chain_Monte_Carlo) can, "handle complex, high-dimensional, and non-standard distributions in financial modeling... it's a powerful tool for pricing, risk management, and uncertainty quantification". [1]

[1] Mistral: "codestral-latest" computed via a [Geneva: abstract](https://geneva.winterdelta.com).

Markov Chain Monte Carlo (MCMC) methods have become a cornerstone of many modern scientific analyses by providing a straightforward approach to numerically estimate uncertainties in the parameters of a model using a sequence of random samples [2]

[2] _"A Conceptual Introduction to Markov Chain Monte Carlo Methods"_ offers a comprehensive intro to the theory: [Joshua S. Speagle |
Center for Astrophysics | Harvard & Smithsonian](https://arxiv.org/abs/1909.12313)
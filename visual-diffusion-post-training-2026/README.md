# Visual Diffusion Post-Training (2026)

A three-part series by [Andrei Filatov](https://anvilarth.github.io/) on
post-training diffusion models for visual generation. It covers how to
improve a pretrained generator's visual quality and prompt following using human
preferences and task-specific rewards: from offline preference optimization to
online reinforcement learning, reward modeling, and balancing multiple rewards.

Slides are in English, recordings are in Russian, and the accompanying blog posts (both RU/EN)
are linked beside each session. Basic background in diffusion
is **needed**; the [Visual GenAI course](../visual_genai_course_2026/README.md) covers
these prerequisites.

## Contents

Follow the sessions in the order below.

| Session | Slides | Recording (RU) | Passcode | Blog post |
| --- | --- | --- | --- | --- |
| 1. Preference Optimization (DPO) | [PDF](slides/Preference%20Optimization.pdf) | [Watch](https://yandex.zoom.us/rec/share/yyxK5rGGZgCHnR0XeOuSM71hoBCDFO4m2jNADXWDmpyV0U0kNQtKSZ_Vb9QmqI7O.PQ1VJkA2Vx2R_yJj) | `Gp+LR4**` | [DPO for Diffusion Models](https://anvilarth.github.io/preference-optimization.html) |
| 2. RL for Diffusion, Part 1 | [PDF](slides/RL%20for%20Diffusion.pdf) | [Watch](https://yandex.zoom.us/rec/share/_qfNZquBydTIR8TICcueHhmMq5LLZ-yYODUmw7QEkzLzhSEAUgKNUn1OAp7C9wGA.BhnXhHmUg9zYuF29) | `c?A&J5S9` | [RL for Diffusion Models, Part 1](https://anvilarth.github.io/rl-for-diffusion-part-1.html) |
| 3. RL for Diffusion, Part 2 | [PDF](slides/RL%20for%20Diffusion%20Part%202.pdf) | [Watch](https://yandex.zoom.us/rec/share/pf1gvXrTCVzYKCaWk9sRCcXtoZD2JS2Amusti6FV9_TaCJncDPLPj1OIN26nrTbf.IqaM__9M4DbQ75b9) | `7%kT5yG+` | [RL for Diffusion Models, Part 2](https://anvilarth.github.io/rl-for-diffusion-part-2.html) |

## Topics covered

- **Preference Optimization:** DPO and Diffusion-DPO, choosing useful preference
  pairs with FiFA, and controlling manifold drift with Rethinking DPO and ThermoDPO.
- **RL for Diffusion, Part 1:** delivering reward signals to the generator through
  direct reward backpropagation (ReFL, DRaFT, DRTune, ShortFT), online policy
  gradients (Flow-GRPO), and reward-weighted training (DiffusionNFT, Advantage
  Weighted Matching).
- **RL for Diffusion, Part 2:** designing and checking reward models (ImageReward,
  VQAScore, VisionReward, RewardDance, SpatialCritic), balancing multiple rewards
  (GDPO, GD²PO, DAPO), and the Qwen-Image-2.0-RL training recipe.

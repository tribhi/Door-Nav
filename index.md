---
layout: default
title: Learning Socially Appropriate Navigation
---

# Learning Implicit Social Navigation Behavior using Deep Inverse Reinforcement Learning

This project explores how robots can learn socially appropriate navigation behavior in dynamic human environments using online human feedback. We introduce a preference-based learning framework that adapts robot navigation strategies based on comparisons provided by non-expert users in simulation and real-world environments.

**Authors:** Tribhi Kathuria, Ke Liu, Junwoo Jang, Maani Ghaffari Jadidi, X. Jessie Yang  
**Published in:** *IEEE Robotics and Automation Letters (RAL)*, 2024  
**DOI:** [10.1109/LRA.2024.3352386](https://doi.org/10.1109/LRA.2024.3352386)

---

## 📄 Paper
- [PDF on arXiv](https://arxiv.org/pdf/2501.06946)
- [IEEE Xplore Link](https://ieeexplore.ieee.org/document/10456795)
- [BibTeX](#citation)

## 🎥 Video (Coming Soon)
<!-- Replace VIDEO_ID with your actual YouTube ID if available -->
<iframe width="560" height="315" src="https://www.youtube.com/embed/VIDEO_ID" frameborder="0" allowfullscreen></iframe>

## 💻 Code (Coming Soon)
The code is released at  
👉 [https://github.com/UMich-CURLY/habicrowd/
tree/main.](https://github.com/UMich-CURLY/habicrowd/
tree/main)

## 🧠 Method Summary
We use a preference-based learning approach to train navigation policies:
- Feedback is collected online from users comparing robot behaviors.
- A reward model is trained using these preferences.
- The robot policy is optimized with reinforcement learning using this learned reward.

The framework is evaluated in both simulated environments and with a real Fetch robot navigating in public spaces.

## 📸 Results
| Scenario                | Human-Liked Trajectories ↑ | Preference Alignment ↑ |
|------------------------|----------------------------|------------------------|
| Simulated CrowdNav     | 85.2%                      | 83.6%                  |
| Real-world Deployments | 78.4%                      | 80.1%                  |

---

## 🔍 Citation
```bibtex
@article{Kathuria2024Learning,
  title={Learning Implicit Social Navigation Behavior using Deep Inverse Reinforcement Learning},
  author={Tribhi Kathuria and Ke Liu and Junwoo Jang and Maani Ghaffari Jadidi and X. Jessie Yang},
  journal={IEEE Robotics and Automation Letters},
  year={2025},
  doi={10.1109/LRA.2025.3557299}
}

# AAAI的提示词：Hierarchical Skill Mining Pipeline

- 归档日期：2026-09-13
- 来源：用户提供的截图，标题为“AAAI的提示词”；不是 AAAI 官方指南。
- 用途：以参考图为视觉和构图依据，生成分层强化学习技能挖掘流程的学术示意图。
- 原始截图：[aaai-skill-mining.jpg](../assets/prompts/aaai-skill-mining.jpg)
- 转录范围：示意图下方的英文提示词，包括 Negative Prompt；图内文字保留在原始截图中，不重复转录。

```text
Use the supplied reference figure as the PRIMARY visual and compositional reference. Create a publication-quality Figure 1 for an AAAI reinforcement learning paper, in a 4:3 landscape format, approximately 2400 × 1800 pixels.

The new figure should closely preserve the reference image’s distinctive visual language, layout proportions, information density, hand-drawn academic infographic style, icon scale, arrow rhythm, border treatment, and typography hierarchy. Do not redesign it as a modern corporate diagram, a polished Nature-style vector illustration, or a futuristic AI interface. The result should immediately look like another figure produced by the same visual design system as the supplied reference, while presenting completely new reinforcement learning content.

SCIENTIFIC TOPIC
The figure presents an LLM-guided Monte Carlo Tree Search framework for automatically discovering reusable hierarchical reinforcement learning skills.
Main centered title:
“Hierarchical Skill Mining Pipeline”
The framework contains four conceptual components:
Skill Search
Agent Tools
Skill Zoo
Policy Building
The overall scientific narrative is:
MCTS explores candidate skill structures; an LLM proposes promising skills and intrinsic rewards; an evaluator filters ineffective candidates; reusable skills are stored in a Skill Zoo; selected skills are composed into a hierarchical reinforcement learning policy and evaluated in simulation.

REFERENCE-ALIGNED GLOBAL LAYOUT
Maintain almost exactly the same high-level composition as the supplied reference.
Place the main title near the top center, occupying approximately 8–10% of the canvas height. Use large black hand-lettered text with slightly irregular strokes. Behind and around the title, add a sparse decorative field of tiny gray and pale-blue dots, similar to a lightly printed halftone cloud. The dots should be subtle and should not interfere with readability.
Below the title, divide the canvas into three white-background rounded rectangular regions:
A. One large orange dashed rounded rectangle on the left, occupying approximately 49–51% of the total canvas width and about 76% of the canvas height.
B. One blue dashed rounded rectangle in the upper-right area, occupying approximately 47% of the canvas width and about 34% of the canvas height.
C. One green dashed rounded rectangle in the lower-right area, occupying approximately 47% of the canvas width and about 39% of the canvas height.
The blue and green right-side rectangles should nearly touch vertically, with only a small white gap between them. Their left edges should align. The orange left rectangle should span the combined height of both right-side rectangles.

Negative Prompt: Sleek corporate infographic, Nature-style polished vector art, futuristic interface, dark background, navy background, gradient-filled panels, glossy 3D icons, isometric illustration, photorealistic robot, cyberpunk UI, rigid symmetrical grid, ultra-clean geometric sans-serif typography, formal academic serif font, thin gray boxes, solid colored panel backgrounds, excessive equations, dense algorithm pseudocode, benchmark plots, result tables, microscopic labels, long paragraphs, complex neural networks, detailed environment screenshots, realistic shadows, cinematic lighting, metallic texture, high-tech dashboard, finance imagery, stock charts, currency symbols, Alpha Search, Alpha Zoo, investment simulation, exact copying of the original text, Chinese screenshot header, source footer, institutional logo, AAAI logo.
```

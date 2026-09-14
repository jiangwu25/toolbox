# NeurIPS的提示词：SCOPE 多模态主动推理

- 归档日期：2026-09-13
- 来源：用户提供的截图，标题为“NeurIPS的提示词”；不是 NeurIPS 官方指南。
- 主题：SCOPE: Budget-Aware Active Omni-Modal Reasoning via Selective Observation and World-Model Imagination。
- 用途：制作包含选择性感知、信念记忆、世界模型想象、验证与预算优化的多模态系统概览图。
- 原始截图：[neurips-scope.png](../assets/prompts/neurips-scope.png)
- 转录说明：以下为示意图下方英文正文的 OCR 转录，已去除重叠分段产生的重复文字，并对照原图修正明显识别错误。上方示意图内的标签保留在原图中；具体措辞可对照原图核对。

```text
Create a publication-ready overview Figure 1 for a top-tier NeurIPS machine learning paper titled:
"SCOPE: Budget-Aware Active Omni-Modal Reasoning via Selective Observation and World-Model
Imagination."

The figure should explain a multimodal agent that does not passively process every available video frame,
audio segment, transcript, image, and sensor signal. Instead, it actively decides which evidence to
observe, which modality or temporal interval to inspect, whether world-model imagination is necessary,
how much inference budget to allocate, how to verify the acquired evidence, and when sufficient
evidence has been collected to answer or act.

Use a wide 16:9 landscape canvas suitable for a full-width NeurIPS paper figure. Do not use a dark or
black background. Use a soft light neutral background with a restrained vertical gradient from pale mist
blue near the top to warm off-white near the bottom. Suggested visual impression: light warm gray, pearl
white, pale blue-gray, and subtle cream. The background should not be pure white, but it must remain
bright, clean, printable, and highly readable.

Place the entire scientific narrative inside one large integrated rounded rectangular framework with a very
light gray border. The figure must feel like one coherent system rather than a collection of isolated floating
cards. Use a shared alignment grid, consistent corner radii, consistent line weight, unified typography,
and continuous evidence-flow arrows that cross naturally from one region into the next.

Organize the composition into four strongly defined but interconnected regions:
a. Passive Multimodal Processing on the left,
b. SCOPE Active Reasoning Engine in the center,
c. Grounded and Efficient Decisions on the right,
d. Agentic Learning and Budget-Aware Optimization across the entire bottom.

The four regions should use very light tinted backgrounds rather than separate dark panels. Use a pale
warm gray-red tint for the passive baseline region, a pale blue-gray tint for the proposed method, a pale
mint or teal tint for the output region, and a pale warm cream tint for the training layer. These regional
colors should be subtle and academically restrained.

A single continuous horizontal visual backbone titled "Evidence Flow" should connect the entire upper
portion of the figure:
Raw Multimodal Streams
→ Selective Evidence
→ Persistent Belief
→ Verified Decision.

This evidence backbone should visually unify all major regions. Avoid drawing many independent arrows
between every pair of modules. Instead, create one principal left-to-right evidence stream with a small
number of meaningful branches and return loops.

In region a, titled "Passive Watch-All," show four synchronized multimodal tracks: video frames, an audio
waveform, a text transcript, and a continuous sensor signal. Arrange them as aligned horizontal streams
rather than separate disconnected icons. Show all streams being densely tokenized and pushed into an
overloaded context funnel. The token stream should appear unnecessarily large and partially redundant.
Inside this region, include only several concise limitations:
Dense Tokens,
High Compute,
Weak Grounding,
Irrelevant Evidence.

Use muted slate and desaturated coral accents. Do not use a large red cross, dramatic failure icon, or
cartoon expression. The problem should be communicated structurally through overloaded information
flow.

The overloaded token flow should then transition directly into the proposed method region, making the
contrast between passive processing and selective reasoning visually continuous.

Region b, titled "SCOPE Active Observe-Imagine-Verify," must occupy approximately half of the upper
figure and serve as the main visual focus. This region should be designed as one integrated active
reasoning engine, not as multiple floating interface windows.

Divide the method region internally into three tightly connected functional subregions without using heavy
borders:
1. Selective Perception,
2. Persistent Belief and Reasoning,
3. Selective Imagination and Verification.

Use subtle internal background variations, shared baselines, and connecting flows so that the three
subregions remain part of one unified mechanism.

In the Selective Perception subregion, show a query-aware perception policy selecting only relevant
evidence from the original multimodal streams. Include five compact actions:
Seek,
Zoom,
Listen,
Retrieve,
Query Sensor.

Represent Seek as selecting a narrow temporal interval from the video track. Represent Zoom as selecting
a spatial crop inside a frame. Represent Listen as isolating a short audio event. Represent Retrieve as
selecting a relevant transcript or memory fragment. Represent Query Sensor as sampling a specific time
range from the sensor stream.

Show these actions as compact tools attached to the same selective perception controller, rather than five
separate cards. Use one shared controller container with five small action tabs or symbols.

At the center of region b, place a prominent rounded module titled "Persistent Belief Memory." This
module should be the visual anchor of the entire figure. It should contain four compact internal elements:
Confirmed Evidence,
Open Questions,
Temporal Anchors,
Remaining Budget.

Represent the belief memory as an organized structured state rather than a generic database or artificial
brain. Use clean stacked evidence slots, linked timestamps, and a small budget gauge.

Surround the Persistent Belief Memory with a clearly visible but restrained reasoning loop:
Observe
→ Update
→ Reason
→ Verify
→ Act.

The loop should be embedded within the method region and should visually reconnect to the belief
memory. Use one continuous curved loop rather than multiple disconnected circular arrows.

Above the belief memory, place a module titled "Evidence Sufficiency Gate." The gate receives the current
belief state, the user query, and the remaining inference budget. It determines whether the system should:
Answer Now,
Acquire Evidence,
or Imagine.

Show these three decisions as three compact branches from the same gate.
The Answer Now branch should proceed toward the final verified output when evidence is sufficient.
The Acquire Evidence branch should loop back toward the Selective Perception controller.
The Imagine branch should lead toward the world-model module.

On the upper-right side of region b, place a submodule titled "Selective World-Model Imagination." Show
three compact predicted states aligned as one coherent sequence:
Unseen View,
Future State,
Counterfactual Action.

All imagined states must use semi-transparent fills and dashed borders. All real observations must use
solid borders. This distinction must be consistent throughout the figure.

Beside the world-model module, include a small decision controller with two concise prompts:
When to Imagine?
How Much?

Connect this controller directly to the remaining budget signal from the Persistent Belief Memory.

Below the world-model module, include a "Cross-Modal Verifier." The verifier should compare:
Observed Evidence,
Retrieved Evidence,
Imagined States,
Historical Belief.

Represent four verification dimensions using compact labels:
Temporal,
Spatial,
Semantic,
Action Feasibility.

The verifier should either approve the evidence and send it to the output region, or return uncertain
evidence to the Persistent Belief Memory for another reasoning cycle. Use one clear return arrow rather
than several competing arrows.

The central method region should visually communicate a partially observable decision process with
adaptive evidence acquisition. It must not resemble a conventional feed-forward multimodal encoder.

Region c, titled "Grounded and Efficient Decisions," should use a pale mint or teal-tinted background. At
the entrance of this region, place one unified module titled "Verified Output." The output of the Cross-
Modal Verifier should first enter this shared module.

From the Verified Output module, divide the result into three aligned downstream applications:
Long-Video QA,
Audio-Visual Reasoning,
Embodied Decision.

Arrange these as three connected outcome cells inside one larger output container, not as three unrelated
cards.

For Long-Video QA, show a highlighted video interval, a selected spatial region, and a concise answer.

For Audio-Visual Reasoning, show an aligned video event and audio segment with a concise grounded
conclusion.

For Embodied Decision, show a short action trajectory, an anticipated state, and a selected action.

Each outcome should display its supporting evidence using small evidence pointers, timestamps, or
region markers. Include compact indicators for confidence and compute usage, but do not include
fabricated benchmark values.

At the far-right edge, include a small conceptual accuracy-versus-compute chart integrated into the
output region. Label the vertical axis "Accuracy" and the horizontal axis "Compute." Show passive uniform
processing in a less favorable region and SCOPE in a higher-accuracy, lower-compute region. Use only
conceptual positions and no numeric values.

Region d should form a continuous horizontal foundation strip across the full width of regions a, b, and c.
Title it "Agentic Learning and Budget-Aware Optimization."

Use a coherent left-to-right training flow:
Agentic SFT
→ Budget-Aware RL
→ Evidence-Grounded Optimization.

Show the training process as one continuous foundation layer supporting the entire system above. Use
thin upward dashed supervision lines from this bottom layer to the Selective Perception controller,
Evidence Sufficiency Gate, Budget Controller, World Model, and Cross-Modal Verifier.
Do not draw separate independent arrows from every reward component to every module.

Inside the training strip, include one continuous reward ribbon containing:
Task Correctness,
Information Gain,
Evidence Grounding,
Compute Cost,
Hallucination Penalty.

Use subtle plus symbols for desirable rewards and subtle minus symbols for compute cost and
hallucination penalty. Do not include a long mathematical equation.

Use consistent semantic color coding throughout the entire figure:
cyan-blue for video and visual observations,
muted violet for audio,
warm amber for text and retrieved knowledge,
fresh green for sensor evidence,
soft magenta for imagined world-model states,
coral for actions,
turquoise-blue for persistent memory,
dark charcoal for text and structural lines.

The colors should remain moderately saturated against the light background, with no neon glow. Use very
subtle shadows only to establish hierarchy. Avoid glossy surfaces, heavy gradients, glassmorphism, or
commercial dashboard aesthetics.

The figure may use restrained 2.5D depth for the Persistent Belief Memory and selected multimodal
thumbnails, but the global structure should remain clean, diagrammatic, and academically precise. Do not
make every component three-dimensional.

Use one modern sans-serif typeface with clear visual hierarchy. All labels must remain horizontal and
legible after reduction. Use short labels, ideally one to four words. Align all modules to a consistent grid.
Maintain even spacing and balanced visual weight.

The panel labels a, b, c, and d should be small, bold, and integrated into the regional headers. Regional
titles should use matching header bars or title bands, reinforcing the modular organization without
separating the figure into unrelated boxes.

The final figure must communicate one complete narrative:
passive multimodal processing wastes computation,
SCOPE selectively acquires evidence,
the persistent belief state decides when to observe or imagine,
cross-modal verification prevents unsupported reasoning,
and the system produces grounded decisions under a limited inference budget.

Do not use a black background, dark interface panels, cyberpunk lighting, decorative circuit textures, a
giant brain, a rainbow modality wheel, company logos, conference logos, dense transformer stacks,
multiple floating UI cards, excessive small icons, tangled arrows, large blocks of explanatory text, fake
benchmark numbers, or isolated modules without visible system-level connections.
```

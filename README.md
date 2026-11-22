# AI Robotics Evaluation & Safety Testing

## Project Overview

This project explores the evaluation of AI-generated responses to robotics scenarios, focusing on safety, task understanding, physical reasoning, perception, spatial reasoning, and decision-making in challenging environments.

Using scenario-based testing, structured human annotation, baseline model predictions, and human–model comparisons, the project investigates whether AI responses demonstrate sound reasoning and adequately account for the risks and constraints associated with robotic tasks.

The goal is to identify reasoning weaknesses, unsafe recommendations, evaluation inconsistencies, and potential failure points in AI systems operating in robotics-related contexts.

## Project Objectives

- Evaluate AI responses to realistic robotics scenarios.
- Assess task understanding and the ability to recognize environmental constraints.
- Examine safety awareness and hazard identification.
- Evaluate spatial and physical reasoning.
- Identify weaknesses in perception, obstacle avoidance, and decision-making.
- Assess how AI responses handle ambiguity, uncertainty, and unexpected conditions.
- Compare human annotations with baseline model predictions.
- Identify disagreements and potential weaknesses in automated evaluation.

## Evaluation Methodology

The project follows a structured evaluation workflow:

1. **Scenario Design** — Develop robotics scenarios involving realistic tasks, environmental conditions, hazards, and constraints.
2. **AI Response Evaluation** — Examine AI-generated responses to determine whether they adequately address the scenario.
3. **Human Annotation** — Apply a structured evaluation rubric to establish reference judgments.
4. **Baseline Model Prediction** — Use a Python-based baseline evaluator to generate predictions against the same evaluation criteria.
5. **Human–Model Comparison** — Compare model predictions against human reference annotations.
6. **Error Analysis** — Examine disagreements, reasoning failures, and safety-related evaluation weaknesses.

## Evaluation Areas

The evaluation framework considers the following criteria, depending on their relevance to each scenario:

| Criterion | Evaluation Focus |
|---|---|
| Overall Verdict | Whether the response is acceptable for the scenario |
| Task Understanding | Whether the AI correctly understands the task and its requirements |
| Safety | Whether it recognizes hazards and prioritizes safe actions |
| Spatial Reasoning | Whether it understands positions, distances, obstacles, and surroundings |
| Physical Reasoning | Whether it accounts for forces, stability, movement, and physical constraints |
| Perception | Whether it correctly interprets relevant objects and environmental conditions |
| Obstacle Avoidance | Whether it identifies obstacles and proposes appropriate responses |
| Edge-Case Awareness | Whether it handles unusual conditions, uncertainty, and unexpected events |

Not every evaluation criterion is applicable to every scenario.

## Robotics Scenarios

The project covers a range of robotics tasks designed to examine different aspects of embodied reasoning and safety.

| Task | Scenario |
|---|---|
| 1 | Collision Avoidance |
| 2 | Force, Balance & Object Interaction |
| 3 | Fragile Glass & Unexpected Obstacle |
| 4 | Moving on a Wet Ramp |
| 5 | Embodied Reasoning: Mug Retrieval in a Kitchen |
| 6 | Human Safety During Maintenance & Intervention |
| 7 | Ambiguity, Edge Cases & Uncertainty Management |

These scenarios explore challenges involving navigation, object manipulation, environmental hazards, physical interactions, human safety, and decision-making under uncertainty.

## Tools & Technologies

- **Label Studio** — Human annotation and structured evaluation
- **Python** — Baseline model evaluation and supporting scripts
- **GitHub** — Project documentation, version control, and portfolio presentation

## Project Scope & Limitations

This project evaluates AI-generated robotics responses using scenario-based and text-based assessments. It is not a physical robotics experiment or a validated robotic safety system.

Baseline model predictions are experimental and are not assumed to represent reliable safety judgments. Human annotations serve as reference evaluations but may also involve subjective interpretation.

The findings are intended to demonstrate practical AI evaluation, annotation, reasoning assessment, and error analysis rather than certify real-world robotic systems.

## Project Status

This is an ongoing practical project. Additional scenarios, annotations, model predictions, comparisons, and findings will be developed as the evaluation progresses.

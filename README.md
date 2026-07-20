# VectorLLM

Project website for **VectorLLM: Language-Controllable Autonomous Driving via
Vectorized Scene Grounding**.

VectorLLM represents vectorized map geometry and agent motion as discrete tokens
inside a pretrained language model. The shared vector-language token sequence
supports driving-scene reasoning, question answering, trajectory generation,
and controllable behavior under scene edits and language instructions.

## Paper

The paper is available at `static/papers/vectorllm.pdf`.

## Website content

- Motivation and contributions
- Scene vectorization and tokenization
- LLM architecture and trajectory generation
- Training and grounded supervision generation
- Evaluation tasks and datasets
- Language-grounding results
- Scene-edit and language-instruction controllability
- Trajectory-forecasting results
- Chain-of-thought, grounding, and scaling analyses
- Limitations

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

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

- Short paper summary
- Driving question-answering examples
- Scene and instruction counterfactual examples
- Unseen-scene captions
- Concise method, results, and limitations

## Local preview

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000`.

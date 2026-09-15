# Generative Music Algorithms

A collection of small, executable composition systems that explore four
different computational ideas: rewriting grammars, Markov chains, cellular
automata, and evolutionary search. Each script produces a MIDI artifact that
can be inspected in a DAW or notation editor.

## Algorithms

| Script | Method | Musical output |
| --- | --- | --- |
| `my_lsystem.py` | Lindenmayer-system rewriting | Expanding chord progressions |
| `markov_melody.py` | Learned transition probabilities | Stochastic melodies |
| `cellular_automaton.py` | Cellular evolution rules | Emergent rhythmic patterns |
| `genetic_melody_harmonizer.py` | Fitness-guided evolutionary search | Chords fitted to a melody |

## Quick start

```bash
git clone https://github.com/takakhoo/GenAI_ChordRhythmChain_Music.git
cd GenAI_ChordRhythmChain_Music
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
python -m pip install -r requirements.txt

python my_lsystem.py
python markov_melody.py
python cellular_automaton.py
python genetic_melody_harmonizer.py
```

Generated MIDI files are written to the working directory. Randomized scripts
may produce a different result on each run.

## Design intent

The value of the collection is comparison: the L-system is deterministic and
structural, the Markov model is locally probabilistic, the automaton creates
emergence from simple rules, and the genetic algorithm makes musical
preferences explicit through a fitness function.

## Repository notes

- `PyTorch Basics/` contains separate learning exercises and is not required by
  the four music generators.
- `Transformer Melody generation` and `generativemusicaicourse` are historical
  reference artifacts.
- The former scheduled auto-commit workflow is retained only for manual
  reference; synthetic activity is intentionally disabled.

## Related work

See [Transformer Melody Generation](https://github.com/takakhoo/Transformer-Melody-Generation)
for the neural sequence-model counterpart to these algorithmic approaches.

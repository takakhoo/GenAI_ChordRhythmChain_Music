# 🎵 My Generative Music Scripts Collection

A comprehensive collection of my personal implementations of cutting-edge generative music algorithms and techniques. This repository showcases various approaches to AI-driven music generation, from mathematical systems to machine learning models.

## 🚀 Featured Projects

### **1. L-Systems for Chord Generation (`my_lsystem.py`)**
- **Algorithm**: Lindenmayer Systems (L-Systems) adapted for musical composition
- **Capability**: Generates complex chord progressions using mathematical transformation rules
- **Innovation**: Treats chord symbols as mathematical symbols with transformation rules
- **Output**: Creates MIDI files with generated chord progressions

### **2. Markov Chain Melody Generation (`markov_melody.py`)**
- **Algorithm**: Markov Chain probability models for sequential music generation
- **Capability**: Learns musical patterns from training data and generates new melodies
- **Innovation**: Uses probability transitions between musical notes
- **Output**: Generates coherent melodies following learned musical patterns

### **3. Cellular Automaton Drum Generation (`cellular_automaton.py`)**
- **Algorithm**: Cellular Automata rules for rhythmic pattern generation
- **Capability**: Creates complex drum patterns using mathematical cellular rules
- **Innovation**: Applies Conway's Game of Life principles to musical rhythm
- **Output**: Generates intricate drum sequences with emergent complexity

### **4. Genetic Algorithm Melody Harmonization (`genetic_melody_harmonizer.py`)**
- **Algorithm**: Genetic Algorithms for evolutionary music composition
- **Capability**: Evolves chord progressions to harmonize given melodies
- **Innovation**: Uses fitness functions based on musical theory principles
- **Output**: Creates harmonized melodies through evolutionary optimization

## 🎯 Technical Highlights

### **Diverse Algorithm Portfolio**
- **Mathematical Systems**: L-Systems, Cellular Automata
- **Probabilistic Models**: Markov Chains
- **Evolutionary Computing**: Genetic Algorithms
- **Machine Learning**: Transformer-based models (see separate repository)

### **Musical Intelligence Features**
- **Chord Generation**: Creates harmonically coherent chord progressions
- **Melody Creation**: Generates musically sensible note sequences
- **Rhythm Generation**: Produces complex rhythmic patterns
- **Harmonization**: Evolves chord progressions to match melodies

### **Advanced Output Capabilities**
- **MIDI Generation**: Exports generated music to MIDI format
- **Music21 Integration**: Uses professional music notation library
- **Real-time Generation**: Creates music through algorithmic processes
- **Customizable Parameters**: Adjustable generation parameters for different styles

## 🛠️ Setup & Installation

### **Environment Setup**
```bash
# Create conda environment
conda create -n MusicAIPractice python=3.8 -y
conda activate MusicAIPractice

# Install dependencies
pip install music21==8.3.0 tensorflow==2.13.0
```

### **Quick Start**
```bash
# Run L-System chord generation
python my_lsystem.py

# Generate Markov chain melodies
python markov_melody.py

# Create cellular automaton drum patterns
python cellular_automaton.py

# Evolve melody harmonizations
python genetic_melody_harmonizer.py
```

## 🎼 Algorithm Deep Dives

### **L-Systems (`my_lsystem.py`)**
- **Principle**: Mathematical rewriting systems for pattern generation
- **Musical Application**: Chord symbols as mathematical symbols with transformation rules
- **Innovation**: A → ABC, B → BA creates complex chord progressions
- **Output**: Generates increasingly complex musical sequences

### **Markov Chains (`markov_melody.py`)**
- **Principle**: Probability-based sequential generation
- **Musical Application**: Learns note transition probabilities from training data
- **Innovation**: Captures musical style and creates coherent melodies
- **Output**: Generates stylistically consistent musical sequences

### **Cellular Automata (`cellular_automaton.py`)**
- **Principle**: Grid-based evolution rules for pattern generation
- **Musical Application**: Applies cellular rules to create rhythmic patterns
- **Innovation**: Emergent complexity from simple rules
- **Output**: Creates intricate drum patterns with natural variation

### **Genetic Algorithms (`genetic_melody_harmonizer.py`)**
- **Principle**: Evolutionary optimization for musical composition
- **Musical Application**: Evolves chord progressions using fitness functions
- **Innovation**: Musical theory principles as evolutionary fitness criteria
- **Output**: Optimizes harmonization through evolutionary pressure

## 🎵 Musical Capabilities

### **Generation Types**
- **Chord Progressions**: Harmonically coherent chord sequences
- **Melodies**: Musically sensible note progressions
- **Rhythms**: Complex rhythmic patterns and drum sequences
- **Harmonizations**: Chord progressions that complement melodies

### **Style Adaptability**
- **Classical**: Traditional harmonic progressions
- **Contemporary**: Modern chord relationships
- **Experimental**: Novel musical structures
- **Customizable**: Adjustable parameters for different styles

## 🚀 Future Enhancements

### **Planned Features**
- **Multi-Track Generation**: Generate harmonies and accompaniments
- **Style Transfer**: Learn and apply different musical styles
- **Real-Time Generation**: Interactive music creation
- **Advanced Visualization**: Visual representation of generation processes
- **Performance Optimization**: GPU acceleration for faster generation

### **Research Directions**
- **Hybrid Algorithms**: Combining multiple generation techniques
- **Machine Learning Integration**: Neural network-based generation
- **Interactive Systems**: Real-time user-guided generation
- **Cross-Genre Learning**: Learning from multiple musical styles

## 🎓 Educational Value

This collection demonstrates:
- **Algorithmic Composition**: Mathematical approaches to music generation
- **Computational Creativity**: AI-driven artistic creation
- **Music Information Retrieval**: Bridging music theory and computer science
- **Diverse Approaches**: Multiple paradigms for generative music
- **Practical Implementation**: Real-world applications of theoretical concepts

## 📚 Learning Resources

Based on the Generative Music AI Course by The Sound of AI, this collection showcases:
- **Mathematical Music Theory**: L-Systems and Cellular Automata
- **Probabilistic Modeling**: Markov Chains for music
- **Evolutionary Computing**: Genetic Algorithms in composition
- **Creative AI**: Artificial intelligence for artistic expression

## 🔗 Related Projects

- **[Transformer Melody Generation](https://github.com/takakhoo/Transformer-Melody-Generation)**: Advanced deep learning approach to melody generation
- **Generative Music AI Course**: Educational resources and implementations

---

*This collection represents a comprehensive exploration of algorithmic music generation, showcasing diverse approaches from mathematical systems to evolutionary computing, all working together to push the boundaries of AI-driven musical creativity.*

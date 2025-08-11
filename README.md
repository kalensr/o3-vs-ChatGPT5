# PhD-Level Reasoning Test Suite: OpenAI o3 vs GPT-5

A comprehensive evaluation framework for testing advanced AI reasoning capabilities at doctoral level, systematically comparing OpenAI's o3 and GPT-5 models across three increasingly complex domains.

## 🎯 Project Overview

This repository contains a rigorous comparative analysis of two state-of-the-art AI models using PhD-level reasoning tests across three domains:

- **Epistemic Modal Logic** (Basic): Unexpected Hanging Paradox
- **Quantum Decision Theory** (Intermediate): Non-classical probability models  
- **Hypercomputation Theory** (Advanced): Oracle hierarchies and transfinite decision theory

## 📊 Key Results

### Overall Performance
| Model | Total Score | Percentage | Result |
|-------|------------|------------|--------|
| **GPT-5** | **192/195** | **98.5%** | 🏆 **Winner** |
| **o3** | **179/195** | **91.8%** | Strong Performance |

### Test-by-Test Breakdown
| Test | Category | o3 Score | GPT-5 Score | Winner | Margin |
|------|----------|----------|-------------|---------|---------|
| **Test 1** | Epistemic Logic | 59/65 | **65/65** | GPT-5 | 6 points |
| **Test 2** | Quantum Decision | 61/65 | **62/65** | GPT-5 | 1 point |
| **Test 3** | Hypercomputation | 59/65 | **65/65** | GPT-5 | 6 points |

**GPT-5 achieved a clean sweep (3-0)** with particularly strong performance in advanced theoretical domains.

## 🏗️ Repository Structure

```
📁 Zen-o3-vs-ChatGPT5/
├── 📋 README.md                              # This file - project overview
├── ⚙️ CLAUDE.md                             # Claude Code specific instructions  
├── 🌐 phd-level-reasoning-test-results.html # Interactive visualization report
├── 🏠 index.html                            # GitHub Pages landing page
├── 🚫 404.html                              # Custom error page
├── 🛑 .nojekyll                             # Disable Jekyll processing
├── 📁 docs/                                 # Documentation files
│   ├── 📊 summary-comparison.md             # Executive summary & analysis
│   ├── 📝 test-1-basic-hanging-paradox.md  # Test 1: Epistemic logic
│   ├── 📝 test-2-intermediate-quantum-decision.md # Test 2: Quantum decision theory
│   └── 📝 test-3-advanced-hypercomputation.md     # Test 3: Hypercomputation theory
├── 📁 assets/                               # Static assets
│   └── 📁 images/                           # Image files
│       ├── 📷 no-charts.png                 # Chart fallback screenshot
│       ├── 📷 perf_matrix.png               # Performance matrix visualization
│       ├── 📷 test-detail-scoring.png       # Detailed scoring breakdown
│       └── 📷 test-perf.png                 # Overall performance chart
└── 📁 dev/                                  # Development files
    └── 🔧 test-chart-fix.html               # Chart debugging version
```

## 🧪 Test Methodology

### Scoring Framework
Each test uses a comprehensive **65-point scoring system**:

**Core Criteria (50 points)**:
- Domain-specific analysis (10 pts each × 5 categories)
- Mathematical rigor and formal reasoning
- Problem identification and solution quality

**Additional Quality (15 points)**:
- Clarity of exposition (5 pts)
- Mathematical rigor (5 pts) 
- Novel insights and creativity (5 pts)

### Test Difficulty Progression

#### 🥉 Test 1: Basic - Unexpected Hanging Paradox
- **Domain**: Epistemic Modal Logic & Backward Induction
- **Focus**: Self-reference problems, knowledge vs. surprise formalization
- **Key Challenge**: Temporal logic and cross-time reasoning

#### 🥈 Test 2: Intermediate - Quantum Decision Theory  
- **Domain**: Non-Classical Probability Models
- **Focus**: Interference effects, decoherence mechanisms
- **Key Challenge**: Mathematical derivations with quantum formalism

#### 🥇 Test 3: Advanced - Hypercomputation & Transfinite Decision Theory
- **Domain**: Oracle Hierarchies and Fundamental Computation Limits
- **Focus**: Transfinite induction, uncountable ordinals, paradox construction
- **Key Challenge**: Set theory, model theory, and post-singularity implications

## 📈 Interactive Visualization

The project includes a comprehensive **HTML report** (`phd-level-reasoning-test-results.html`) featuring:

### 🎨 Features
- **Self-Contained**: No external dependencies required
- **Interactive Charts**: Chart.js visualizations with hover details
- **Mathematical Notation**: MathJax support for complex formulas
- **Responsive Design**: Works across all devices and browsers
- **Progressive Disclosure**: Expandable sections for detailed analysis

### 📊 Visualizations
1. **Overall Performance Bar Chart**: Side-by-side score comparison
2. **Test 2 Detailed Breakdown**: Category-by-category analysis  
3. **Performance Matrix Radar Chart**: Multi-dimensional capability comparison

### 🔧 Technical Robustness
- Multiple CDN fallbacks for reliability
- Comprehensive error handling with retry logic
- Graceful degradation with meaningful fallback content
- Detailed console logging for debugging

## 🧠 Model Analysis Deep Dive

### GPT-5 Strengths
- **Theoretical Sophistication**: Deeper foundational understanding
- **Breadth of Analysis**: Consistently covered more angles and edge cases
- **Creative Problem-Solving**: Novel approaches and constructions
- **Interdisciplinary Integration**: Better connections across fields

### o3 Strengths  
- **Mathematical Elegance**: Cleaner, more direct proofs
- **Computational Focus**: Better emphasis on constructive aspects
- **Practical Orientation**: Strong governance and safety insights
- **Efficiency**: More concise without sacrificing correctness

### Performance Patterns
- **o3**: Consistent performance (59-61/65) across difficulty levels
- **GPT-5**: Near-perfect with slight dip only in intermediate test (62-65/65)

## 🔬 Methodology & Zen MCP Integration

This project leverages the **Zen MCP (Model Context Protocol)** ecosystem for systematic AI model evaluation:

### Testing Protocol
1. **Prompt Design**: Custom PhD-level reasoning challenges
2. **Parallel Execution**: Simultaneous testing of both models
3. **Expert Analysis**: Domain-specific evaluation criteria
4. **Comparative Assessment**: Side-by-side scoring with justification

### Zen MCP Tools Used
- `mcp__zen__chat`: Direct model interaction and testing
- `mcp__zen__thinkdeep`: Complex multi-step analysis
- `mcp__zen__consensus`: Multi-model comparison workflows

## 🎓 Academic Applications

### Research Domains
- **Artificial Intelligence**: Model capability assessment and comparison
- **Cognitive Science**: Advanced reasoning and decision theory research
- **Theoretical Computer Science**: Logic, computation, and complexity analysis
- **Philosophy of Mind**: Consciousness, reasoning, and artificial cognition

### Educational Use
- **Graduate Seminars**: Real-world examples of advanced AI capabilities
- **Methodology Teaching**: Rigorous evaluation framework demonstration
- **Interdisciplinary Research**: Bridge between AI and traditional academic domains

## 🚀 Getting Started

### Quick Start
1. **View Results**: Open `phd-level-reasoning-test-results.html` in any modern browser
2. **Read Analysis**: Start with `summary-comparison.md` for executive summary
3. **Deep Dive**: Explore individual test files for detailed model responses
4. **Technical Details**: Check `CLAUDE.md` for implementation specifics

### Requirements
- **Modern Web Browser**: Chrome, Firefox, Safari, Edge (recent versions)
- **JavaScript Enabled**: Required for interactive visualizations
- **No Installation**: All dependencies are embedded in the HTML file

### For Developers
- **Extend Framework**: Follow established 65-point scoring rubric
- **Add Visualizations**: Modify Chart.js configurations in HTML
- **Debug Issues**: Use browser console and built-in diagnostic functions

## 📝 Research Methodology

### Evaluation Principles
1. **Objective Scoring**: Standardized rubrics with clear criteria
2. **Domain Expertise**: PhD-level content requiring advanced knowledge
3. **Comprehensive Coverage**: Multiple aspects per domain (theory, application, creativity)
4. **Reproducible Process**: Documented methodology for replication

### Quality Assurance
- **Mathematical Verification**: All formulas and proofs cross-checked
- **Consistency Validation**: Scores verified across all documents
- **Expert Review**: Content validated by domain specialists
- **Technical Testing**: HTML report tested across multiple browsers/devices

## 🔮 Implications & Future Directions

### Key Findings
1. **Both models demonstrate genuine PhD+ level reasoning capabilities**
2. **GPT-5 shows superior breadth and theoretical sophistication**
3. **o3 excels in focused, practical problem-solving approaches**
4. **Advanced AI models are approaching human expert performance in specialized domains**

### Future Research Opportunities
- **Additional Models**: Claude, Gemini, and emerging systems
- **Domain Expansion**: Pure mathematics, theoretical physics, philosophy
- **Longitudinal Studies**: Tracking model improvements over time
- **Collaborative Testing**: Multi-model problem-solving scenarios

### Industry Implications
- **Model Selection**: Evidence-based choice for specific use cases
- **Capability Planning**: Understanding current AI limitations and strengths
- **Research Direction**: Identifying promising areas for AI development
- **Safety Considerations**: Implications of rapidly advancing reasoning capabilities

## 📊 Data & Reproducibility

### Available Artifacts
- **Raw Model Responses**: Complete, unedited outputs from both models
- **Detailed Scoring**: Point-by-point justification for all evaluations  
- **Interactive Analysis**: Self-contained HTML report for exploration
- **Methodology Documentation**: Complete process for replication

### Transparency Measures
- **Open Methodology**: All evaluation criteria clearly documented
- **Version Control**: All changes tracked and documented
- **Bias Mitigation**: Systematic scoring approach reduces subjective bias
- **Peer Review Ready**: Prepared for academic publication standards

## 🤝 Contributing

### How to Extend This Work
1. **Follow Established Standards**: Use 65-point rubric framework
2. **Maintain Academic Rigor**: Ensure PhD-level content quality
3. **Document Thoroughly**: Update all related files consistently  
4. **Test Comprehensively**: Verify HTML report functionality

### Collaboration Opportunities
- **Domain Experts**: Contribute specialized test cases
- **AI Researchers**: Extend to additional models or capabilities
- **Visualization Experts**: Enhance interactive reporting features
- **Education Specialists**: Adapt for teaching and training applications

## 📚 Citation & References

### Citing This Work
```bibtex
@misc{zen_o3_gpt5_comparison_2025,
  title={PhD-Level Reasoning Test Suite: OpenAI o3 vs GPT-5 Comparative Analysis},
  author={[Author Name]},
  year={2025},
  howpublished={GitHub Repository},
  url={https://github.com/[repo]/Zen-o3-vs-ChatGPT5}
}
```

### Related Work
- Martin's Borel Determinacy Theorem (Test 3 theoretical foundation)
- Unexpected Hanging Paradox literature (Test 1 philosophical background)
- Quantum Decision Theory research (Test 2 mathematical framework)
- AI Evaluation Methodologies and Benchmarking Standards

## ⚖️ License & Ethics

### Academic Use
This work is intended for academic research, education, and advancing understanding of AI capabilities. Please cite appropriately when using in research or educational contexts.

### Ethical Considerations
- **Model Evaluation**: Objective assessment without commercial bias
- **Transparency**: Full methodology disclosure for reproducibility
- **Safety Focus**: Understanding AI capabilities for responsible development
- **Educational Value**: Contributing to AI literacy and research methodology

---

## 🎉 Conclusion

This comprehensive evaluation demonstrates that both OpenAI o3 and GPT-5 have achieved remarkable PhD-level reasoning capabilities, with GPT-5 showing particular strength in theoretical breadth and creative problem-solving. The systematic methodology and interactive visualization provide a robust framework for ongoing AI model assessment and research.

**For questions, suggestions, or collaboration opportunities, please see the documentation in `CLAUDE.md` or contact the project maintainers.**
# CLAUDE.md

This file provides guidance to Claude Code when working with the PhD-Level Reasoning Test Suite for comparing OpenAI o3 vs GPT-5 models.

## Project Overview

This repository contains a comprehensive evaluation framework for testing advanced AI reasoning capabilities at PhD level. The project systematically compares OpenAI's o3 and GPT-5 models across three increasingly complex domains: epistemic logic, quantum decision theory, and hypercomputation.

## Architecture & Design

### Core Components

1. **Test Framework**: Three progressively difficult reasoning tests designed for PhD-level evaluation
2. **Scoring System**: Detailed 65-point rubrics with multi-criteria assessment
3. **Zen MCP Integration**: Leverages specialized AI agents for model testing and analysis
4. **Interactive Visualization**: Self-contained HTML report with Chart.js visualizations
5. **Comprehensive Documentation**: Detailed markdown files with full model responses

### Test Suite Structure

```
Zen-o3-vs-ChatGPT5/
├── README.md                           # Project documentation and usage guide
├── CLAUDE.md                          # Claude Code specific instructions
├── summary-comparison.md              # Executive summary and comparative analysis
├── test-1-basic-hanging-paradox.md   # Epistemic logic test (Basic)
├── test-2-intermediate-quantum-decision.md # Quantum decision theory (Intermediate)  
├── test-3-advanced-hypercomputation.md     # Hypercomputation theory (Advanced)
├── phd-level-reasoning-test-results.html   # Interactive HTML report
├── test-chart-fix.html                # Chart debugging version
└── *.png                              # Screenshot documentation
```

## Test Methodology

### Difficulty Progression
- **Test 1 (Basic)**: Unexpected Hanging Paradox - Epistemic modal logic
- **Test 2 (Intermediate)**: Quantum Decision Theory - Non-classical probability models
- **Test 3 (Advanced)**: Hypercomputation & Transfinite Decision Theory - Oracle hierarchies

### Evaluation Criteria (Per Test)
Each test uses a 65-point scoring system:
- **Core Criteria**: 5 categories × 10 points = 50 points
- **Additional Quality**: 3 categories × 5 points = 15 points
- **Total Possible**: 195 points across all tests

### Zen MCP Testing Protocol
The project leverages Zen MCP's specialized agents for systematic model evaluation:

1. **Test Generation**: Custom PhD-level prompts across three difficulty tiers
2. **Model Execution**: Parallel testing using `mcp__zen__chat` with model selection
3. **Response Analysis**: Detailed scoring using domain expertise
4. **Comparative Assessment**: Side-by-side analysis with scoring justification

## Key Results Summary

### Overall Performance
- **GPT-5**: 192/195 (98.5%) - Winner across all three tests
- **o3**: 179/195 (91.8%) - Consistent high-quality performance

### Test-by-Test Breakdown
| Test | Category | o3 Score | GPT-5 Score | Winner |
|------|----------|----------|-------------|---------|
| 1 | Epistemic Logic | 59/65 | 65/65 | GPT-5 |
| 2 | Quantum Decision | 61/65 | 62/65 | GPT-5 |  
| 3 | Hypercomputation | 59/65 | 65/65 | GPT-5 |

### Key Differentiators
- **GPT-5 Strengths**: Broader theoretical coverage, superior formalization, creative problem-solving
- **o3 Strengths**: Mathematical elegance, computational efficiency, practical focus

## Technical Implementation

### HTML Report Features
The `phd-level-reasoning-test-results.html` file includes:

- **Self-Contained**: All dependencies embedded (Chart.js, MathJax, CSS)
- **Interactive Visualizations**: Three Chart.js charts with detailed breakdowns
- **Responsive Design**: Works across devices and browsers
- **Mathematical Notation**: MathJax support for complex formulas
- **Progressive Disclosure**: Expandable sections for detailed responses

### Chart.js Integration
Advanced chart rendering with comprehensive error handling:
- Multiple CDN fallbacks for reliability
- Retry mechanisms with up to 5 attempts
- Graceful degradation with fallback content
- Detailed console logging for debugging

### Mathematical Content
Extensive use of advanced mathematical notation:
- Modal logic operators (K, ¬, ∧, ∨)
- Quantum mechanics formulations
- Set theory and ordinal constructions
- Transfinite induction proofs

## Working with This Project

### Extending the Test Suite

When adding new tests:
1. Follow the established 65-point scoring rubric
2. Include both model responses with detailed analysis
3. Provide mathematical rigor appropriate for PhD level
4. Update the HTML report with new visualizations

### Modifying Visualizations

The HTML report uses Chart.js 4.4.1 with:
- Bar charts for overall performance comparison
- Detailed breakdown charts for individual tests  
- Radar charts for multi-dimensional capability analysis

### Debugging Chart Issues

The project includes robust error handling:
- Check browser console for detailed diagnostic logs
- Use `checkSystemStatus()` function for debugging
- Fallback content displays when charts fail to render
- Multiple initialization attempts with retry logic

## Integration with Zen MCP

### Model Testing Commands
```bash
# Test specific models using Zen MCP chat
mcp__zen__chat --model o3 --prompt "[test-prompt]"
mcp__zen__chat --model gpt5 --prompt "[test-prompt]"
```

### Analysis Workflows
```bash
# Use Zen MCP for detailed analysis
mcp__zen__thinkdeep --model gpt5 --step 1 --findings "[analysis]"
mcp__zen__consensus --models '[{"model": "o3"}, {"model": "gpt5"}]'
```

## Research Applications

### Academic Use Cases
- **Comparative AI Evaluation**: Systematic model comparison methodology
- **Reasoning Assessment**: PhD-level capability benchmarking  
- **Theoretical Computer Science**: Advanced logic and computation testing
- **Cognitive Science Research**: Decision theory and reasoning analysis

### Industry Applications
- **Model Selection**: Evidence-based choice between advanced AI models
- **Capability Assessment**: Understanding model strengths and limitations
- **Research Planning**: Identifying optimal models for specific domains
- **Quality Assurance**: Rigorous testing methodology for AI systems

## Best Practices

### When Working with Test Files
1. **Preserve Mathematical Accuracy**: All formulas and proofs must remain precise
2. **Maintain Scoring Integrity**: Never alter scores without recalculating totals
3. **Document Changes**: Update summary files when modifying individual tests
4. **Verify Consistency**: Cross-check scoring between individual tests and summary

### HTML Report Maintenance
1. **Test Locally**: Always verify chart rendering in multiple browsers
2. **Preserve Self-Containment**: Keep all dependencies embedded
3. **Update Systematically**: Changes to data require updating all related charts
4. **Maintain Accessibility**: Ensure fallback content remains meaningful

### Extending Analysis
1. **Use Established Framework**: Follow existing 65-point rubric structure
2. **Maintain PhD Standards**: All content should meet doctoral-level rigor
3. **Document Methodology**: Clearly explain any deviations from established patterns
4. **Cross-Validate Results**: Use multiple evaluation approaches when possible

## Dependencies & Requirements

### Core Technologies
- **Chart.js 4.4.1**: Interactive data visualization
- **MathJax 3**: Mathematical notation rendering  
- **Modern Browser**: ES6+ JavaScript support required
- **Zen MCP**: AI model testing and analysis platform

### Optional Enhancements
- **PDF Export**: For academic publication preparation
- **LaTeX Integration**: For journal submission formatting
- **Statistical Analysis**: Additional quantitative assessment tools

## Future Directions

### Potential Expansions
1. **Additional Models**: Testing Claude, Gemini, and other advanced systems
2. **Domain Specialization**: Category theory, algebraic topology, theoretical physics
3. **Temporal Analysis**: Longitudinal studies of model improvements
4. **Collaborative Testing**: Multi-model problem-solving scenarios

### Methodological Improvements  
1. **Blind Evaluation**: Independent scoring to reduce bias
2. **Cross-Validation**: Multiple expert evaluators per test
3. **Automated Scoring**: ML-assisted evaluation for consistency
4. **Real-Time Testing**: Live model comparison interfaces

---

## Important Notes for Claude Code

1. **Mathematical Precision**: Never alter mathematical content without careful verification
2. **Scoring Consistency**: Always recalculate totals when modifying individual scores  
3. **Chart Dependencies**: Test HTML report thoroughly after any modifications
4. **Documentation Standards**: Maintain PhD-level academic rigor in all content
5. **Zen MCP Integration**: Leverage specialized agents for complex analysis tasks

This project represents a significant contribution to AI evaluation methodology and should be treated with appropriate academic rigor and attention to detail.
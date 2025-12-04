# CONTRIBUTING

Thank you for your interest in contributing to the **Global Crisis 2025-2050** research project! This is an open research initiative, and we welcome contributions from researchers, practitioners, students, and engaged citizens.

---

## Types of Contributions

We welcome contributions in many forms:

### Research Contributions
- **New Chapters**: Expand analysis into new crisis domains
- **Case Studies**: Detailed analysis of specific crises, countries, or systems
- **Regional Analysis**: Deep dives into specific geographic regions
- **Methodological Papers**: New analytical approaches and frameworks
- **Literature Reviews**: Synthesis of recent research in specific areas

### Data Contributions
- **Conflict Data**: Updated information on active conflicts
- **Economic Indicators**: New datasets on inequality, development
- **Climate Data**: Environmental indicators and projections
- **Technology Metrics**: AI development, digital trends
- **Social Data**: Trust surveys, polarization indices, migration flows

### Quality Assurance
- **Fact-Checking**: Verify claims and identify errors
- **Source Validation**: Confirm data sources and citations
- **Peer Review**: Critical evaluation of analysis and conclusions
- **Methodology Review**: Assessment of analytical approaches

### Content Enhancement
- **Visualizations**: Charts, graphs, interactive dashboards
- **Code**: Simulations, models, automation scripts
- **Documentation**: Clarifications, examples, tutorials
- **Examples**: Real-world applications of concepts

### Translation
- **Spanish** (Español)
- **French** (Français)
- **Arabic** (العربية)
- **Mandarin** (中文)
- **Other languages**: Contact maintainers

### Community Building
- **Event Organization**: Workshops, seminars, discussion groups
- **Outreach**: Help spread awareness of the research
- **Collaboration**: Connect researchers and practitioners
- **Funding**: Help secure resources for the project

---

## Getting Started

### 1. Fork the Repository
```bash
# Go to https://github.com/magictreesproductions/global-crisis-2025-2050
# Click "Fork" button in upper right
```

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR_USERNAME/global-crisis-2025-2050.git
cd global-crisis-2025-2050
```

### 3. Create a Feature Branch
```bash
# Use descriptive branch names
git checkout -b feature/your-contribution-name

# Examples:
git checkout -b feature/sahel-crisis-update
git checkout -b feature/quantum-computing-analysis
git checkout -b feature/spanish-translation
```

### 4. Make Your Changes

Follow the style guides for your contribution type (see below).

### 5. Commit with Descriptive Messages
```bash
git commit -m "Add [type]: [description]

Detailed explanation of changes and why they were made.
- Bullet point 1
- Bullet point 2

Closes #123 (if addressing an issue)"
```

### 6. Push to Your Fork
```bash
git push origin feature/your-contribution-name
```

### 7. Submit a Pull Request

Go to your fork on GitHub and click "New Pull Request". Provide:
- **Title**: Clear, descriptive PR title
- **Description**: Detailed explanation of changes
- **Related Issues**: Reference any related issues (#123)
- **Checklist**: Confirm PR meets quality standards

---

## Style Guides

### Research Contributions

**Markdown Format**:
```markdown
# Chapter Title

## Section Heading

### Subsection

**Bold for emphasis** and *italics for terms*.

- Bullet points for lists
- Use consistent formatting

> Block quotes for important statements

[Links](to-sources.md) with clear references
```

**Citation Format**:
```markdown
According to [source][1], the metric is X.

[1] Author, Year. "Title." Journal/Publisher.
```

**Data Presentation**:
```markdown
| Metric | 2023 | 2025 | Growth |
|--------|------|------|--------|
| Water Use (Texas) | 20B | 49B | 52% annually |
```

### Data Contributions

**Format**:
- JSON for structured data
- CSV for tabular data
- GeoJSON for geographic data

**Metadata**:
```json
{
  "name": "Dataset Name",
  "source": "Original source",
  "date": "2025-12-05",
  "description": "What this data represents",
  "methodology": "How data was collected",
  "limitations": "Known limitations and caveats",
  "last_updated": "2025-12-05"
}
```

### Code Contributions

**Language**: Python preferred, but all languages welcome

**Format**:
```python
"""
Module description with purpose and usage.
"""

def function_name(param1, param2):
    """
    Brief description.
    
    Args:
        param1: Description
        param2: Description
        
    Returns:
        Description of return value
    """
    # Implementation with clear comments
    pass
```

**Documentation**: Include docstrings and comments

**Testing**: Include test cases for code contributions

---

## Quality Standards

### Research Quality
- [ ] Based on credible sources with proper citations
- [ ] Distinguishes between facts, analysis, and speculation
- [ ] Acknowledges limitations and uncertainties
- [ ] Considers alternative perspectives
- [ ] Peer-reviewed or reviewed by domain experts

### Data Quality
- [ ] From reliable sources
- [ ] Properly documented with metadata
- [ ] Includes data quality notes
- [ ] Citations for all data sources
- [ ] Regular updates/versioning

### Writing Quality
- [ ] Clear, concise language
- [ ] Proper grammar and spelling
- [ ] Consistent formatting
- [ ] Appropriate for target audience
- [ ] Well-organized and logical flow

### Code Quality
- [ ] Well-commented and documented
- [ ] Follows Python style guide (PEP 8)
- [ ] Includes error handling
- [ ] Tested and working
- [ ] Reproducible results

---

## Review Process

### 1. Initial Review (1-3 days)
- Check for completeness and format compliance
- Verify files are in correct locations
- Request clarifications if needed

### 2. Content Review (3-7 days)
- Assess quality of contribution
- Check citations and sources
- Evaluate claims and analysis
- Request revisions if necessary

### 3. Peer Review (Optional)
- Subject matter expert review
- Methodological critique
- Suggestions for improvement

### 4. Integration (1-3 days)
- Merge approved pull requests
- Update related documentation
- Create release notes

### 5. Feedback
- Provide constructive feedback
- Suggest improvements
- Thank contributors

---

## Communication Guidelines

### Be Respectful
- Assume good intentions
- Engage thoughtfully with disagreements
- Avoid personal attacks
- Respect diverse perspectives

### Be Clear
- Explain your reasoning
- Provide context
- Link to relevant information
- Ask clarifying questions

### Be Constructive
- Focus on ideas, not people
- Suggest improvements, not just criticism
- Offer to help solve problems
- Recognize good contributions

### Be Collaborative
- Work with others toward common goals
- Share knowledge and expertise
- Celebrate successes
- Learn from failures

---

## Reporting Issues

Use GitHub Issues for:
- **Bugs**: Errors in data, code, or analysis
- **Inaccuracies**: Factual errors or outdated information
- **Feature Requests**: New content, visualizations, or tools
- **Questions**: Clarifications about research or methods
- **Discussions**: Open-ended topics for community input

---

## Recognition and Attribution

Contributors are recognized in multiple ways:

### In-Project Recognition
- Listed in [CONTRIBUTORS.md](CONTRIBUTORS.md)
- Credited in commit history
- Mentioned in release notes
- Featured in project updates

### External Recognition
- Academic citations (if applicable)
- Co-authorship on published papers
- Speaking opportunities at events
- Project leadership roles

---

## Code of Conduct

All contributors agree to:

1. **Be Inclusive**: Welcome people of all backgrounds and perspectives
2. **Be Respectful**: Treat all people with dignity and respect
3. **Be Honest**: Present information truthfully and acknowledge uncertainties
4. **Be Collaborative**: Work together toward shared goals
5. **Be Constructive**: Focus on improving the project, not personal conflicts

Violations of this code may result in removal from the project.

---

## Questions?

### Documentation
- See [README.md](README.md) for project overview
- Check [PROJECT_OVERVIEW.md](docs/PROJECT_OVERVIEW.md) for research questions
- Review [METHODOLOGY.md](docs/METHODOLOGY.md) for analytical approaches

### Contact
- **Issues**: Use GitHub Issues for project-related questions
- **Discussion**: Use GitHub Discussions for broader conversations
- Contact via GitHub

### Getting Help
- Review existing issues and pull requests
- Check discussion history
- Ask in GitHub Discussions

---

## Thank You!

Thank you for contributing to this important research. Your efforts help build the comprehensive understanding needed to address the interconnected global crises of 2025-2050.

Together, we can create the knowledge base for a better future.

---

**Last Updated**: December 2025  
**Version**: 1.0  
**Maintained By**: @mag00s

For updates and guidelines changes, see the [CONTRIBUTING history](https://github.com/magictreesproductions/global-crisis-2025-2050/commits/main/CONTRIBUTING.md).

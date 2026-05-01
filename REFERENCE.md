# Academic Writing Reference

## 1. Scientific Formatting
### Units
- Use SI units consistently (kg, m, s, N, J, W).
- Always include a space between the number and the unit (e.g., `10 kg`, not `10kg`).

### Equations
- Use Markdown LaTeX formatting for inline and block equations.
- **Inline**: `$F = ma$`
- **Block**:
  ```
  $$ \tau = r \cdot F \sin(\theta) $$
  ```

## 2. Citation Styles
### APA Style (Default)
- **In-text**: (Author, Year)
- **Reference List**: Author, A. A. (Year). *Title of work*. Publisher.

### IEEE Style (Engineering/IoT)
- **In-text**: [1]
- **Reference List**: [1] A. Author, "Title of paper," *Journal Name*, vol. X, no. Y, pp. Z-ZZ, Year.

## 3. Specialized Terminology & Nomenclature
### Physical & Biological Sciences
- **Physics**: Angular velocity ($\omega$), Torque ($\tau$), Reynolds Number ($Re$).
- **Microbiology**: *Escherichia coli* (Italicize scientific names), CFU (Colony Forming Units).

### AI & Data Science
- **Computer Vision**: CNN, YOLO, Segmentation, Feature Extraction.
- **NLP**: Transformers, BERT, LLMs, Sentiment Analysis, NER.
- **Core ML**: Regression, Clustering, Decision Trees, SVM.
- **Deep Learning**: Backpropagation, Gradient Descent, GANs.

### Digital Agriculture
- **Sensing**: NDVI, Multispectral, Hyperspectral Imaging.
- **Platforms**: IoT Gateways, Cloud Analytics, Edge Computing.
- **Action**: Variable Rate Irrigation (VRI), Autonomous Farm Robots.

## 4. Academic Rank Standards (รศ.)
- **Originality**: Emphasis on "Original Synthesis" (การสังเคราะห์ความรู้ใหม่).
- **Practical Application**: Integration with local context (e.g., Thai Agriculture, Tropical Climate).
- **Pedagogy**: Use of Bloom's Taxonomy for learning objectives in Teaching Documents.

## 5. Coding Standards for Academia
### Python (Data Science & AI)
- Use PEP 8 standards.
- Include Docstrings for all functions/classes.
- Provide comments for complex mathematical implementations.
- **Example**: `plt.title()`, `sns.heatmap()` for data visualization.

### Flutter (UI & App Dev)
- Focus on Clean Architecture or BLoC pattern for state management.
- Documentation of Widget trees and API integrations.
- **Example**: `SfCartesianChart` for visualizing IoT data in Flutter.

## 6. Systematic Project Structure
Maintain the following hierarchy for textbook projects:
```text
[Project_Name]/
├── main.tex             # Main LaTeX driver
├── book.md              # Consolidated Markdown version
├── chapters/            # Folder per chapter
│   ├── ch1_intro/
│   │   ├── ch1.md       # Chapter content (Markdown)
│   │   ├── ch1.tex      # Chapter content (LaTeX)
│   │   ├── code/        # Python/Flutter source files
│   │   └── images/      # Diagrams and plots
│   └── ...
└── references.bib       # BibTeX citations
```

## 7. Logical Flow
1. **Premise**: State the physical/scientific law or AI principle.
2. **Application**: Apply to the specific domain (e.g., Agri, Env).
3. **Evidence**: Provide data, calculation, or code simulation.
4. **Inference**: High-level synthesis for the Associate Professor rank.

# Group Project Guide – Python Programming & Version Control

## Overview
The group project is a core component of this course where you’ll apply everything you’ve learned to create a Python application. You’ll work in teams of 4–5 students to design, implement, and present a scientific computing project.

**Project Duration:** Weeks 1–6  
**Presentation:** Week 6 (15 minutes + 5 minutes Q&A)  
**Weight:** 30% of final grade

## Learning Objectives
By completing this project, you will:
- Apply object-oriented programming principles to a problem
- Use Git and GitHub for collaborative development
- Analyze and visualize scientific data using pandas and matplotlib
- Write clean, documented, and well-structured code
- Present technical work to an audience
- Work effectively in a team on a coding project

## Project Requirements

### 1. Technical Requirements

#### Object-Oriented Design
- At least 3 custom classes with meaningful relationships
- Use of inheritance OR composition (or both)
- Implementation of appropriate magic methods (e.g., `__str__`, `__repr__`, `__eq__`)
- Properties for data validation/encapsulation where appropriate

#### Data Handling
- Read data from files (CSV, TXT, JSON, or other formats)
- Use pandas DataFrames for data analysis
- Handle potential errors (file not found, invalid data, etc.)

#### Visualization
- At least 2–3 different plot types using matplotlib
- Clear labels, titles, and legends on all plots
- Plots should communicate scientific insights

#### Version Control
- Code hosted on GitHub
- Regular commits throughout the project (not all at the end!)
- Meaningful commit messages
- Evidence of collaboration (multiple contributors)

#### Documentation
- Docstrings for all classes and methods
- README file with:
  - Project description
  - Installation instructions
  - Usage examples
  - Team member contributions
- Comments for complex code sections

#### Testing
- Code should run without errors
- Test with sample data to verify correctness
- Handle edge cases (empty data, invalid inputs, etc.)

### 2. Scope Guidelines

**Appropriate Scope:**
- Achievable in 4–6 weeks with team of 4–5 students
- Focuses on demonstrating course concepts
- Has a clear scientific application
- Complex enough to showcase skills, but not overwhelming

**Too Small:**
- Single class with basic functions
- No data analysis or visualization
- Can be completed in 2–3 hours

**Too Large:**
- Machine learning model with extensive training
- Web application with database backend
- Requires external APIs or services not covered in course

**Rule of Thumb:**  
If you can implement the core functionality in Week 2, your scope is too small.  
If you’re not sure you can finish by Week 5, your scope is too large.

## Project Timeline

### Week 1: Form Teams & Choose Topic
**Action Items:**
- Form groups of 4–5 students
- Brainstorm project ideas
- Choose your project topic
- Identify what data you’ll need
- Fill out the group contract
- Set up GitHub repository

**Deliverable:** Upload your group contract on Canvas

### Week 2: Design & Setup
**Action Items:**
- Design your class structure (draw a class diagram)
- Start README
- Find/create sample data for testing
- Implement core classes and methods

### Week 3: Core Implementation
**Action Items:**
- Begin data reading functionality
- Write tests for basic functionality
- Regular commits to GitHub

**Milestone:** Core classes working with sample data

### Week 4: Data Analysis & Visualization
**Action Items:**
- Implement data analysis features
- Create visualizations with matplotlib
- Add error handling
- Begin documentation

**Milestone:** Full functionality working, first plots generated  
**Deliverable:** Submit your GitHub repository for peer review

### Week 5: Finalization
**Action Items:**
- Complete all features
- Polish documentation (README, docstrings)
- Create presentation slides
- Practice presentation as a team
- Final testing and debugging
- Integrate the received feedback

**Deliverables:**
- Final code committed to GitHub
- README complete
- Presentation slides ready

### Week 6: Presentations
**Action Items:**
- Present your project (15 min)
- Answer questions (5 min)
- Watch other teams present

**Deliverable:** Live presentation + working demo  
**Deliverable:** Submit GitHub link for your finalised project (as release)

## Project Ideas by Scientific Domain

### Biology / Life Sciences
1. **DNA/Protein Sequence Analyzer**
   - Classes: Sequence (parent), DNA, RNA, Protein
   - Features: GC content, ORF finding, translation, motif search
   - Data: FASTA files
   - Plots: GC distribution, sequence length histograms, motif locations

2. **Population Dynamics Simulator**
   - Classes: Species, Population, Ecosystem
   - Features: Logistic growth, predator–prey models, competition
   - Data: Initial populations, parameters from literature
   - Plots: Population over time, phase space diagrams

3. **Phylogenetic Tree Builder**
   - Classes: Species, TreeNode, PhylogeneticTree
   - Features: Distance calculation, tree construction, visualization
   - Data: Sequence alignments or distance matrices
   - Plots: Tree visualization, distance heatmaps

### Chemistry
1. **Chemical Reaction Network Simulator**
   - Classes: Molecule, Reaction, ReactionNetwork
   - Features: Concentration tracking, rate equations, equilibrium
   - Data: Reaction definitions, initial concentrations
   - Plots: Concentration vs time, reaction rates

2. **Molecular Property Calculator**
   - Classes: Atom, Bond, Molecule
   - Features: Molecular weight, formula, structure properties
   - Data: SMILES strings or molecular formulas
   - Plots: Property distributions, structure comparisons

3. **Acid-Base Titration Analyzer**
   - Classes: Solution, Titration, Buffer
   - Features: pH calculation, equivalence point, buffer capacity
   - Data: Titration data (volume, pH)
   - Plots: Titration curves, derivative plots

### Physics
1. **Particle Physics Simulator**
   - Classes: Particle, Force, System
   - Features: Motion under gravity, electrostatics, collisions
   - Data: Initial positions, velocities, masses
   - Plots: Trajectories, energy over time, phase space

2. **Wave Phenomena Analyzer**
   - Classes: Wave, Medium, Interference
   - Features: Superposition, standing waves, diffraction
   - Data: Wave parameters (frequency, amplitude)
   - Plots: Wave patterns, interference patterns, spectra

3. **Thermodynamics Calculator**
   - Classes: System, Process, Cycle
   - Features: Work, heat, entropy calculations
   - Data: State parameters (P, V, T)
   - Plots: PV diagrams, process cycles

### Environmental Science / Earth Science
1. **Climate Data Analyzer**
   - Classes: Station, Measurement, ClimateDataset
   - Features: Temperature trends, anomaly detection
   - Data: Historical climate data (CSV)
   - Plots: Time series, trend lines, anomaly maps

2. **Water Quality Monitor**
   - Classes: Sample, Parameter, WaterBody
   - Features: Quality indices, trend analysis, threshold alerts
   - Data: Water quality measurements
   - Plots: Parameter trends, quality scores, spatial distributions

### Mathematics / Statistics
1. **Statistical Distribution Analyzer**
   - Classes: Distribution (parent), Normal, Binomial, etc.
   - Features: Parameter estimation, hypothesis testing
   - Data: Experimental or simulated data
   - Plots: PDFs, CDFs, Q–Q plots, histograms

2. **Numerical Methods Library**
   - Classes: Function, DifferentialEquation, Integrator
   - Features: Root finding, integration, ODE solving
   - Data: Function definitions, initial conditions
   - Plots: Solution curves, error analysis, convergence

### Interdisciplinary
1. **Scientific Instrument Data Processor**
   - Classes: Instrument, Measurement, Calibration
   - Features: Data import, calibration, quality control
   - Data: Instrument output files
   - Plots: Calibration curves, measurement distributions

2. **Experiment Planner & Tracker**
   - Classes: Experiment, Trial, Protocol
   - Features: Design tracking, result recording
   - Data: Experimental parameters and results
   - Plots: Result comparisons, success rates

## Team Roles (Suggested)
- **Project Manager:** Meetings, deadlines, task tracking
- **Lead Developer:** Code structure, PR reviews
- **Data Specialist:** Data handling, pandas analysis
- **Visualization Specialist:** Matplotlib plots, visuals
- **Documentation Lead:** Docstrings, README, slides

*Note:* Everyone should code. These are coordination roles.

## GitHub Workflow

### Setting Up
1. One team member creates a repository on GitHub
2. Add other team members as collaborators
3. Everyone clones the repository
4. Create a `.gitignore` file

### Daily Workflow
```bash
git pull origin main
git add .
git commit -m "Descriptive message"
git push origin main
```

### Best Practices
- Commit often
- Write clear commit messages
- Pull before pushing
- Test before committing
- Don’t commit large data files

## Presentation Guidelines

### Structure (15 minutes)
1. Introduction (3 min)
2. Technical Overview (3 min)
3. Implementation Highlights (4 min)
4. Demo (4 min)
5. Conclusion (1 min)

### Tips
- Practice together
- Everyone speaks
- Prepare backup screenshots
- Time yourselves

## Evaluation Criteria
- Code Quality (40%)
- Functionality (25%)
- Documentation (15%)
- Version Control (10%)
- Presentation (10%)

## Common Pitfalls
- Starting too late
- Poor communication
- Uneven contribution
- Overambitious scope
- No testing
- Missing documentation
- No demo backup

## Resources
- pandas
- matplotlib
- numpy
- scipy

## Submission Checklist
(As listed in original document)

## Example Project Structure
```
my-science-project/
 README.md
 requirements.txt
 .gitignore
 src/
 data/
 examples/
 tests/
 docs/
```

## Academic Integrity
You may discuss ideas and use documented resources.  
You may not copy code from other teams or outsource your work.

If you use external code, cite it:
```python
# Adapted from: https://stackoverflow.com/questions/12345/
def my_function():
    pass
```

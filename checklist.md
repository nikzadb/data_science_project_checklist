# Checklist

## 1. Answering the Question

- [ ] Did you specify the type of data analytic question (e.g. exploration, association causality) before touching the data?
- [ ] Did you define the metric for success before beginning?
- [ ] Did you understand the context for the question and the scientific or business application?
- [ ] Did you record the experimental design?
- [ ] Did you consider whether the question could be answered with the available data?

##  2. Checking the Data

- [ ] Did you plot univariate and multivariate summaries of the data?
- [ ] Did you check for outliers?
- [ ] Did you identify the missing data code?

## 3. Tidying the Data

- [ ] Is each variable one column?
- [ ] Is each observation one row?
- [ ] Do different data types appear in each table?
- [ ] Did you record the recipe for moving from raw to tidy data?
- [ ] Did you create a code book?
- [ ] Did you record all parameters, units, and functions applied to the data?

## 4. Exploratory Analysis

- [ ] Did you identify missing values?
- [ ] Did you make univariate plots (histograms, density plots, boxplots)?
- [ ] Did you consider correlations between variables (scatterplots)?
- [ ] Did you check the units of all data points to make sure they are in the right range?
- [ ] Did you try to identify any errors or miscoding of variables?
- [ ] Did you consider plotting on a log scale?
- [ ] Would a scatterplot be more informative?

## 5. Inference

- [ ] Did you identify what large population you are trying to describe?
- [ ] Did you clearly identify the quantities of interest in your model?
- [ ] Did you consider potential confounders?
- [ ] Did you identify and model potential sources of correlation such as measurements over time or space?
- [ ] Did you calculate a measure of uncertainty for each estimate on the scientific scale?

## 6. Prediction

- [ ] Did you identify in advance your error measure?
- [ ] Did you immediately split your data into training and validation?
- [ ] Did you use cross validation, resampling, or bootstrapping only on the training data?
- [ ] Did you create features using only the training data?
- [ ] Did you estimate parameters only on the training data?
- [ ] Did you fix all features, parameters, and models before applying to the validation data?
- [ ] Did you apply only one final model to the validation data and report the error rate?

## 7. Causality

- [ ] Did you identify whether your study was randomized?
- [ ] Did you identify potential reasons that causality may not be appropriate such as confounders, missing data, non-ignorable dropout, or unblinded experiments?
- [ ] If not, did you avoid using language that would imply cause and effect?

## 8. Written analyses

- [ ] Did you describe the question of interest?
- [ ] Did you describe the data set, experimental design, and question you are answering?
- [ ] Did you specify the type of data analytic question you are answering?
- [ ] Did you specify in clear notation the exact model you are fitting?
- [ ] Did you explain on the scale of interest what each estimate and measure of uncertainty means?
- [ ] Did you report a measure of uncertainty for each estimate on the scientific scale?

## 9. Figures

- [ ] Does each figure communicate an important piece of information or address a question of interest?
- [ ] Do all your figures include plain language axis labels?
- [ ] Is the font size large enough to read?
- [ ] Does every figure have a detailed caption that explains all axes, legends, and trends in the figure?

## 10. Presentations

- [ ] Did you lead with a brief, understandable to everyone statement of your problem?
- [ ] Did you explain the data, measurement technology, and experimental design before you explained your model?
- [ ] Did you explain the features you will use to model data before you explain the model?
- [ ] Did you make sure all legends and axes were legible from the back of the room?

## 11. Reproducibility

- [ ] Did you avoid doing calculations manually?
- [ ] Did you create a script that reproduces all your analyses?
- [ ] Did you save the raw and processed versions of your data?
- [ ] Did you record all versions of the software you used to process the data?
- [ ] Did you try to have someone else run your analysis code to confirm they got the same answers?

## 12. Code Packages

- [ ] Did you make your package name “Googleable”
- [ ] Did you write unit tests for your functions?
- [ ] Did you write help files for all functions?
- [ ] Did you write a vignette?
- [ ] Did you try to reduce dependencies to actively maintained packages?
- [ ] Have you eliminated all errors and warnings?

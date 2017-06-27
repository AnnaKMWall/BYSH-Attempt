#Introduction to Multilevel Models {#ch-multilevelintro}

##Learning Objectives
  After finishing this chapter, you should be able to:

- Recognize when response variables and covariates have been collected at multiple (nested) levels.
- Apply exploratory data analysis techniques to multilevel data.
- Write out a multilevel statistical model, including assumptions about variance components, in both by-level and composite forms.
- Interpret model parameters (including fixed effects and variance components) from a multilevel model, including cases in which covariates are continuous, categorical, or centered.
- Understand the taxonomy of models, including why we start with an unconditional means model.
- Select a final model, using criteria such as AIC, BIC, and deviance.

##Case Study: Music Performance Anxiety {#cs:music}

\setlength{\parindent}{7ex}
\indent Stage fright can be a serious problem for performers, and understanding the personality underpinnings of performance anxiety is an important step in determining how to minimize its impact.  Sadler and Miller (2010) studied the emotional state of musicians before performances and factors which may affect their emotional state.  Data was collected by having 37 undergraduate music majors from a competitive undergraduate music program fill out diaries prior to performances over the course of an academic year.  In particular, study participants completed a Positive Affect Negative Affect Schedule (PANAS) before each performance.  The PANAS instrument provided two key outcome measures:  negative affect (a state measure of anxiety) and positive affect (a state measure of happiness).  We will focus on negative affect as our primary response measuring performance anxiety.  \par

\indent Factors which were examined for their potential relationships with performance anxiety included:  performance type (solo, large ensemble, or small ensemble); audience (instructor, public, students, or juried); if the piece was played from memory; age; gender; instrument (voice, orchestral, or keyboard); and, years studying the instrument.  In addition, the personalities of study participants were assessed at baseline through the Multidimensional Personality Questionnaire (MPQ).  The MPQ provided scores for one lower-order factor (absorption) and three higher-order factors: positive emotionality (PEM--a composite of well-being, social potency, achievement, and social closeness); negative emotionality (NEM--a composite of stress reaction, alienation, and aggression); and, constraint (a composite of control, harm avoidance, and traditionalism). \par

Primary scientific hypotheses of the researchers included:

- Lower music performance anxiety will be associated with lower levels of a subject's negative emotionality.
- Lower music performance anxiety will be associated with lower levels of a subject's stress reaction.
- Lower music performance anxiety will be associated with greater number of years of study.

##Initial Exploratory Analyses {#explore}

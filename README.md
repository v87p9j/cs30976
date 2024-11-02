java cStorytelling Presentation 
The goal is to effectively present your analytics project and convince the audience to adopt your recommendation. This is an individual assignment.
You are free to use any tools such as Excel, Mathematica, Matlab, Minitab, Python, R, SAS, SPSS, SQL, Tableau, etc.
Before you start, I recommend watching top storytelling presentations in:
Storytelling Hall of Fame 
Guidelines 
Dataset 
You can use one or more dataset(s) of your choice. A few good places to find one are kaggle.com, data.gov, healthdata.gov, archive.ics.uci.edu, or kdnuggets.com. However, your dataset should:
● include at least 10 variables except for columns of ID and unary (or nearly unary) variables.
● include at least 1,000 records (rows).
● be new to you. Using a dataset from your prior project is prohibited.
Failure to meet these conditions will result in a zero mark.
The goal is to bring interesting insights of your own. To that end, I recommend choosing a larger dataset (e.g., with 20 columns and 10,000 rows) as far as you can manage it. From more columns, you may find more influential features leading to more accurate models and richer insights. With more rows, data partitions are more flexible in case of overfitting. Please avoid a dataset including a number of columns with high multicollinearity since most of them may have to be removed later so that few influential features are left. I also recommend choosing a dataset in the domain of your field, major, or interest for strong business understanding. You may want to start with some quick EDA of a few datasets to see if you can find some interesting initial insights and then choose one of them.
Format 
You will record a 6-minute presentation in an mp4 video. The typical rule of thumb is about 1 per minute. So, you may have about 6 main slides for the core content, excluding the opening slide (presentation title, your name, etc.) and the closing slide (e.g., QA, Thank you, etc.). These slides should be followed by an appendix of references, charts, tables, outputs, etc.
Your presentation should cover the entire CRISP-DM phases and below are the grading points I consider.
● Business understanding
○ Brief the business context of the client. Note: If you do not have a direct client, suppose potential clients who may use your analysis. For deeper business understanding, I recommend using some articles on the domain.
○ Propose a few research questions and discuss why they are important to the client(s).
● Data understanding
○ Discuss the results of EDA. Note: EDA is never enough. Do much EDA and include the details in the appendix.
○ Variable selection – Discuss variable importance and multicollinearity. Note: Consider correlations, chi-squares, etc.
○ Report skewed variables and their skewness.
○ Report outliers or confirm that your dataset is free of them. Note: I recommend box plots. Are they genuine outliers or data errors?
○ Data quality – Report data errors or duplicate records. Or confirm that your dataset is free of them.
○ Report missing values or confirm that your dataset is free of them.
○ Identify promising subsets (of rows) (if needed). Note: Your business understanding may help. I also recommend clustering.
● Data and modeling preparation
○ Handle outliers (if any).
○ Remove errors or duplicate records (if any).
○ Handle missing values (if any). Note: Removing a variable with missing values should be the last resort. Perform. imputation and/or flagging before removal. Imputation using regression or decision tree is recommended. I do not recommend replacement with mean or median.
○ Binning (discretizing) numerical variables and/or reclassifying categorical variables (if needed)
○ Combining multiple datasets.
○ Sampling or balancing (if needed)
○ Data scaling or standardization (if needed)
○ Transform. skewed variables (if you plan to choose regression in modeling). Note: De-transform. later before interpreting the regression coefficients.
○ Data partition for cross-validation
● Modeling and model evaluation
○ Model comparison – Use at least three different models. I also recommend using at least two different options for each model. Discuss how the models are different and how you choose the final model.
○ Error or accuracy measures (e.g., ASE (average square error), MSE (mean square error), s, r2, adjusted r2, misclassification rate, lift, ROC (receiver operating characteristic), etc.) – Select some measures and discuss why you use the chosen measures.
○ Show cross-validation results using errors or graphs. If you detect overfitting, discuss how you have resolved the issue.
● Conclusion
○ Summarize the most salient findings and provide actionable recommendations regarding the research questions.
○ Support conclusion accurately and clearly based on analysis. Do not offer unsupported recommendations.
○ Your conclusion should be unique and insightful. Do not inclu代 写Storytelling PresentationPython
代做程序编程语言de findings like common sense, e.g., a strong relationship between Sales (target) and Units sold (feature).
○ You should not use technical terms in conclusion. Use plain languages which can be understood by anyone who has no knowledge of data mining.
● Limitation
○ Discuss the limitations of your project. Note: Show that you understand the limitations.
○ Suggest ways to improve your project if you have a chance to do it again.
● Appendix — Note: Appendix is required, not optional.
○ Include references, charts, tables, outputs, etc.
○ The appendix may be as long as possible, but make sure to refer to it when needed during presentation. If it is too long, consider submitting it in a separate document.
Submission 
Submit PowerPoint (or PDF), mp4 recording, raw data, and prepared/cleaned data files(s) to: Modules => Storytelling => Storytelling Presentation.
● Document your slides and record an mp4 video.
● Have your raw and prepared/cleaned data files ready. Note: Failure to submit the data files will result in a zero mark.
● Name your files as: Storytelling_Presentation_First_Name_Last_Name. So, if your name is Satoshi Nakamoto, please name your files as:
Storytelling_Presentation_Satoshi_Nakamoto.pptx (or .pdf)
Storytelling_Presentation_Satoshi_Nakamoto.mp4
Storytelling_Raw_Data_Satoshi_Nakamoto.xlsx (or .csv)
Storytelling_Prepared_Data_Satoshi_Nakamoto.xlsx (or .csv)
Note:  If you use Tableau in your presentation, please submit your twbx file, too.
● Submit files. Links to external documents or recordings embedded in slides are not accepted.
● Unless you get my pre-approval in cases of technical or other issues, email submissions are not allowed.
Grading 
Your presentation will be graded for a full mark of 38 points with the criteria (and their relative importance) below.
● Information selection and organization (24)
○ Information amount ‒ Provides an ideal quantity of information.
○ Information relevance ‒ Includes relevant and necessary information at an appropriate level of detail.
○ Information sequence ‒ Sequences information logically and persuasively.
○ Information flow ‒ Linking statements create a good flow of ideas.
● Design and delivery (12)
○ Engaging ‒ Captures and holds audience attention.
○ Professional ‒ Exceeds or meets professional expectations for the modality (oral communication).
○ Visual aids ‒ Effectively designs and uses visual aids for message and audience.
○ Error-free ‒ Has no preventable mistakes or errors.
● Time (2)
You have 6 minutes to present. Your presentation time will be graded as below.Points 
Time range (minutes) 2 
5:30 ≤ Time ≤ 6:30 1 
5:00 ≤ Time < 5:30 or 6:30 < Time ≤ 7:00 0 
Time < 5:00 or 7:00 < Time 
Advice from the past presentations 
● Professional communications are clear, articulate, and natural.
○ I encourage you to review the LinkedIn materials below to polish up your presentation.
— Dewitt, T. (2019). How to present and stay on point. (19m) LinkedIn Learning.
— Kolovou, T. (2019). Creating and giving business presentations. (1h 16m) LinkedIn Learning.
— Shander, B. (2022). Data visualization: A lesson and listen series. (16h) LinkedIn Learning. (Watch Chapters 2 to 6.)
● Make no spelling/grammatical errors and pronounce all terms correctly.
● Practice, practice, and practice!
○ This can help you present seamlessly at a more consistent pace, control presentation time better, and keep eye contact with the audience.
● Tell an interesting story.
○ Business understanding and conclusion are the critical steps where you can engage the audience. For example, a few interesting research questions and their significance based on strong business understanding are a good starting point.
○ Your conclusion should answer and echo the research questions. So, I recommend revising or fine-tuning the research questions after you list up the most salient findings and recommendations in the conclusion.
● Choose and design visual elements carefully.
○ Avoid slide templates with nice graphics but allocate little space for content.
○ Be mindful of the limited space in the main slides and use it wisely. For example, rather than copy and paste a table of outputs onto a slide and only refer to one or two of the outputs, consider having only those outputs on the slide. If needed, locate the entire table in the appendix.
○ All letters and numbers should be large enough to be readable.
○ Your charts should ensure fair comparison. For example, heights/widths of bars should be proportional to the corresponding statistics/numbers. You may need trial-and-errors with different graph options.
○ All labels should be large enough to be readable. If they are too small and difficult to enlarge, consider attaching a new larger label.
○ Avoid putting multiple charts on one slide, except when you are comparing the charts.



         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com

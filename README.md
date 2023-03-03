# df-capstone-project
## Background

- Formula 1 is the highest class of open wheel single seater racing and there is a large
- The sport has altered dramatically over the last 20 years, the target of my project, changing hands from Bernie Ecclestone’s F1 Group to Chase Carey’s Liberty Media
- Thanks to the dramatic 2021 title fight between Lewis Hamilton and Max Verstappen, and global influence from Netflix's Drive to Survive Series  viewers are at their highest ever levels globally since 2008, with Sky attracting 2.3 million viewers in the UK alone for a race, the highest ever audience for a pay per view broadcaster

## Driver prediction importance

- Predicting the result of a race consistently, thanks to random variables such as reliability, accidents and multiple potential winners, is almost impossible without diving into very specific details only available to manufacturers
- However, there is still merit in seeing whether a driver leaves a team or not
- Being able to make driver predictions could be beneficial for teams to know if a driver maybe considering retirement, and also if results are mirroring those of a driver that leaves, to consider whether they should be making a better financial decision as well
- It is worth considering that a driver is sometimes kept for more than just driver merit, some drivers known have wealthy investors putting money into the team, often with the objective with securing the drive of a specific driver for family or brand image reasons
- This level of data is not readily available and so this will not be studied, although I will attempt to see of there is correlation between constructor and driver nationality as sometimes this can affect keeping a driver on for team popularity in a home country

## Key strategies
- This project compares and fine tuned different modelling such as logistical regression and random forest/decision trees to find the best predictor of a driver's likely move
- Works on the assumption that a driver and constructor not matching in consecutive years constitues a move, assigned a 1, against a 0 for a match
- Models then trained on a selction of the data against a test set
- Assume that drivers don't stay with a team for a single reason, however in most cases retirement, promotion, relegation and being dropped from the sport for political reasons all play a part

#### Please note that the workbook may not work in the context of the current csv file location as this work was done on a different device to where it has been pushed from, this can be fixed by ensuring that the location of the running .ipynb workbook is in the same working directory as the .csv files in f1_data

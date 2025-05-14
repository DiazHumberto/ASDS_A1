# Applied Statistics for Data Science

This is a project about Exploratory Data Analysis using python.

## About Dataset
This is a census dataset about the adult income in the USA in the 1990s. The
sample in this dataset was extracted by Barry Becker from the 1994 Census
database and now is open source by the University of California, Irvine.
Here I provide a clean version.

Each entry contains the following information about an individual:
- **age:** the age of an individual (Integer > 0)
- **workclass**: a general term to represent the employment status of an
individual (Private, Self­ emp­ not­ inc, Self­ emp­ inc, Federal­ gov, Local­ gov,
State­ gov, Without­ pay, Never­ worked)
- **fnlwgt:** final weight. In other words, this is the number of people the census
believes the entry represents (Integer > 0)
- **education:** the highest level of education achieved by an individual
(Bachelors, Some­ college, 11th, HS­ grad, Prof­ school, Assoc­ acdm, Assoc­ voc,
9th, 7th­ 8th, 12th, Masters, 1st­ 4th, 10th, Doctorate, 5th­ 6th, Preschool).
- **education.­num:** the highest level of education achieved in numerical form
(Integer > 0)
marital­ .status: marital status of an individual. Married­ civ­ spouse corresponds
to a civilian spouse while Married­ AF­ spouse is a spouse in the Armed Forces
(Married­ civ­ spouse, Divorced, Never­ married, Separated, Widowed,
Married­ spouse­ absent, Married­ AF­ spouse).
- **occupation:** the general type of occupation of an individual (Tech­ support,
Craft­ repair, Other­ service, Sales, Exec­ managerial, Prof­ specialty,
Handlers­ cleaners, Machine­ op­ inspct, Adm­ clerical, Farming­ fishing,
Transport­ moving, Priv­ house­ serv, Protective­ serv, Armed­ Forces).
- **relationship:** represents what this individual is relative to others. For example
an individual could be a Husband. Each entry only has one relationship
attribute and is somewhat redundant with marital status (Wife, Own­ child,
Husband, Not­ in­ family, Other­ relative, Unmarried)
- **race:** Descriptions of an individual’s race (White, Asian­ Pac­ Islander,
Amer­ Indian­ Eskimo, Other, Black)
- **sex:** the biological sex of the individual (Male, Female)
- **capital.­gain:** capital gains for an individual (Integer > 0)
- **capita.lloss:** capital loss for an individual (Integer > 0)
- **hours.­per.­week:** the hours an individual has reported to work per week
(Integer > 0)
- **native.­country:** country of origin for an individual (United­ States, Cambodia,
England, Puerto­ Rico, Canada, Germany, Outlying­ US(Guam­ USVI­ etc), India,
Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy,
Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France,
Dominican­ Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary,
Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El­ Salvador,
Trinadad&Tobago, Peru, Hong, Holand­ Netherlands).
This repository contains code and data for the manuscript "Memory failure predicts belief regression after the correction of misinformation", forthcoming in the journal Cognition (available at https://authors.elsevier.com/c/1fphK2Hx2pj3L). 

The data file, `data.csv`, contains the following columns: 

* `Condition`: participants’ experimental condition (1 = Control, 2 = Belief first correction, 3 = Memory first correction)
* `Education`: measured on a 1-6 scale, where 1 = did not finish high school and 6 = Advanced/postgraduate degree
* `Gender`: 1 = Male, 2 = Female, 3 = Other/Prefer to self-describe
* `Age`
* `Party.General`: participants’ reported political party (Democrat, Republican, Independent)
* `Party.Closer`: participants’ political leaning if they responded “Independent” to Party.General (closer to Democratic/Republican Party, Neither)

* Columns starting with `BF` contain belief formation scores (0-10 scale), where participants answered, "How much have you considered this item in the past?"
* Columns starting with `S_` contain surprise ratings (0-10) scale, where participants answered, "How surprised are you that this item was true/false?"
* Columns containing `Pre`, `Imm`, and `Month` represent memory (starts with `M`, e.g., `MImm`) or belief (starts with `B`, e.g., `BImm`) scores at a particular time point (0-10 scale). 

It is important to note that items 1-16 were misinformation items, and items 17-32 were true items. 

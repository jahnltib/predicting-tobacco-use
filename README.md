# To Do:

(Done) Merged multi-choice questions into single columns.
() Impute missing values that are NaN (very low amount)
() Impute (S, N, Z) values (think about how to deal)
() Decide what to do with (S) true skip values?
() Perform a stratified test/train split (important to do before encoding) 
() Encoded categorical features using target encoding (ask chatgpt why test/train split first is important)
   -- ordinal features need to either be unchanged or should preverse their ordinality (where order matters)
   -- nominal features need to be target encoded.

Some resources I found:
https://www.blog.trainindata.com/target-encoder-a-powerful-categorical-encoding-method/
https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.TargetEncoder.html#sklearn.preprocessing.TargetEncoder


Kai:
modified_data.xlsx is only for reference. I include the modified dataset for better visualization on excel. 

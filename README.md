# STEM-Village
A personal research project on LGBTQ people in STEM following the Twitter account (TheSTEMvillage). 
The objective was to determine how many Transgender people work in STEM fields and what particular fields are they in, as to address the primary question of how many Transgender people work in Software Development/ Programming. A dataset was created which will not be publically available for safety concerns, but can be email requested.

## Inclusion Criteria
The inclusion criteria for accounts to be added to the dataset had to: 
- have pride flag(s)
- have pronouns, any account with `they` were added to the `Transgender` column
- state what STEM related field of study or work (a hashtag or Twitter account of department was also used)



## Data Collection Process
- First pass at data collecting was looking by hand at the accounts, quickly looking for pride flags. Any account that had a pride flag but with `Ally` were excluded. My first pass gathered 580 accounts.
- Twitter API was used to scrape the total amount of accounts that follow the TheSTEMvillage, but this approach was not suitable to the data I was gathering, as Twitter Bio text is not collected along with the various columns of data. I collected 6678 followers but ultimately none of this data was used in my dataset.
- Second pass at data collecting was returning to the 580 accounts and reading the Bio/ About the Twitter user information. The step was the process of reading and classification of `field of study` into general categories, along with pronouns. 
- 92 accounts were deleted due to these accounts not having field of study or occupation stated. Attempts were made at determining type of work or study. The dataset has 488 completed rows.
- For some field of study classifications such as `Biology` or `Biologist` include all types of Biologists, Planetary Biology would be in this category. Classifications were made for brevity and generalization of science field. 


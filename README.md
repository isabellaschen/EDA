# EDA
EDA Case Study - NYU

Presentation of Important Findings:
https://docs.google.com/presentation/d/1pE_DLT0JoUDAVQKnmN5py9i5JSc22N-GF0bNIx3PARM/edit?usp=sharing 

Overview:
We split up work based on the Current and Previous Application data. Much of the initial work was exploratory, to figure out what data was most significant. Grant also did a lot of work to clean-up the data, which can be viewed on a separate notebook: https://colab.research.google.com/drive/1KkyiWKqC0778s4YawNi2rSMwZECFV6_9?usp=sharing. We primarily worked with the target column, to create a 'default_rate' that we were able to compare across many categories. While the previous application data didn't have that same target column, we create approval and denial rates to explore the applicant and application features that were most often approved and denied. A higher denial rate is usually indicative of a higher risk of default.

Primary Findings:
- Default rates decrease with higher levels of education
- Default rates increase with with lower-skilled workers
- Non-defaultors typically have a higher score from credit bureaus
- Approval rates generally decrease with number of requested loans, and denial rates of risker loans are higher
  - The ratio of approval to denials widens for safer loans

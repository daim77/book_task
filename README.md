# book_task
**interview_task | book recommendation problem**

Jupiter notebook is for engine developmnet and data analysis. You can find remarks for explanations.

DATA MANIPULATION
- Book title is written in one string format
- Country is extracted from location
- Age is trimmed from outliers

.py file is streamlit application, which reads data from database and can present data to user visually.
streamlit is only as dashboard.

__requirements:__

local DB
data stored as was downloaded from server
Due to SQL Alchemy = MySQL or its fork is required

folder with screenshot shows streamlit app

__ENGINE evaluation__
PROS:
- it is simple
- good results with really useful tips

CONS:
- problem is with threshold for minimum ranks (now set to eight)
- correlation mainly dealing with low number of values - set is significantly cut
- very often no recommendation (random book is possible)
- no dealing with age or region
- no book category in database

__new engine??__
- API for book category?
- or choos books rated by same users as for favorite book, filter users according region and select 3 more frequent book
or three of them on random basis with ratings more plus minus 1 from favorite book for example



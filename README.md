part 1: 
we are structure the job description with the help of pydantic and llm call.

part 2:
Resume parsing -
we are targeting to information in cv.
first, we individually structure the experience because , experience play crucial role in shortlisting of candidates.
then , extract the meaningful information based resume schema. 

part 3:
we are extract the text from resume (ex - .pdf and .docx).
and send to the resume parser.

part 4:
we provide the structure JSON Job description and resume to LLM.
then LLM provide the score and short concise reason .

part 5:
then, we sort the candidate according to score and show top candidates.
You can also see the worst candidates according to your need.

Using technquies and technology :

I use the LLM to do the intellectual task.
and also use pydantic to structure the job description and resume information.
some general libraries are - os , pathlib, time, Groq, pydantic , pypdf, docx and dotenv.

if you want to run the ats
first you use the uv to create necessary folder.

uv init-ATS
cd ATS

#create virtual environment 

uv venv

#the activate

source .venv/bin/activate

uv run ats.py



# https://www.juliabloggers.com/how-to-call-julia-code-from-python/
FROM abelsiqueira/python-and-julia:py3.10-jl1.6

COPY requirements.txt requirements.txt
COPY main.py main.py

RUN pip install -r requirements.txt

CMD ["uvicorn", "main:app", "--reload"]

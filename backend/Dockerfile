FROM python

WORKDIR backend

COPY . /backend

RUN pip install -r req.txt

EXPOSE 8000:80

CMD [ "python" ,"app.py" ]

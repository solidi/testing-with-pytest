FROM python:3

ADD test_slower.py /
ADD test_slower_2.py /

RUN pip install pytest

CMD [ "pytest", "test_slower.py" ]
CMD [ "pytest", "test_slower_2.py" ]
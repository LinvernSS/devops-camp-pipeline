FROM python:3.9
COPY / ./app-dir/
WORKDIR app-dir
RUN /bin/sh -c 'pip install --no-cache-dir --index-url https://nexus.dev.afsmtddso.com/repository/jxu-test-repo/simple -r requirements.txt'
ENTRYPOINT ["python"]
CMD ["server.py"]

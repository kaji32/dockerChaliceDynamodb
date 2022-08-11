FROM python:3.8-alpine

WORKDIR /app

RUN pip install chalice
RUN pip install awscli --upgrade --user

# added for aws cli

# RUN curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
# RUN unzip awscliv2.zip
# RUN sudo ./aws/install

CMD [ "/bin/sh"]
FROM python:3.8.14 as dev

# create user with user ID 1002 (= grandl on DGX) in group md_ai inside container
RUN groupadd -g 1002 md_ai
RUN useradd --shell /bin/bash --create-home -g md_ai -u 1002 HSD

WORKDIR /home/HSD
FROM debian:stable-slim
LABEL maintainer="enrico.simonetti@gmail.com"

RUN adduser sugar --disabled-password --disabled-login --gecos ""

COPY apps/sugarfixpermissions /usr/local/bin/sugarfixpermissions
RUN chmod +x /usr/local/bin/sugarfixpermissions

CMD ["/usr/local/bin/sugarfixpermissions"]

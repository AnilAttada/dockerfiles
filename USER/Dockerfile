FROM almalinux:9
RUN dnf install nginx -y
RUN useradd anilkumar

USER anilkumar
CMD ["nginx" , "-g" , "daemon off;"]
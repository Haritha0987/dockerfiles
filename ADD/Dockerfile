FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html 
ADD https://raw.githubusercontent.com/Haritha0987/shell-practice-from-shiva/refs/heads/main/10-install-command.sh /usr/share/nginx/html/index.html  
RUN chmod +r /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "deamon off;"]
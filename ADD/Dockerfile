FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/Nagendra-1304/Expense-shell/blob/main/backend.service /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]
FROM node:16-alpine
EXPOSE 3000
WORKDIR /app/back-end
ADD node_modules.tar.gz .
COPY . .
ENTRYPOINT ["npm"]
CMD ["start"]

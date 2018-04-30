## Build
`docker build -t recipe-book-server:prod .`

## Run
`docker run -d --name recipe-book-server -p 3000:3000 recipe-book-server:prod`
 # template-docker-www

## setup
- [X] Create a repository from the templatew

## publish (Mobirise)
- [X] clone to local machinesa
- [X] checkout a new branch
- [X] publish web content into the ```publish``` foldersss
- [x] verify pushas
- [X] merge into main when happys
- [X] execute the build github actions xcb
- [ ]   VEFY IMPORTANT - the image name has to escape the slash in the image name so it should be ```maverick1542\/web:latest```a
- [ ] this will ctreatem a ```docker-compose.yml``` filedfggfdgfgdffgdask
- [ ] this will create a docker image (named as you input)ssss ss
- [ ] once completed click on the Workflow summary and you'll see 2 artifactsssskokoss
ssa
## publish (3rd Party)sdfsdfsfdsdfsdsaaa
- [X] download the docker-compose zip and extract sssaa
- [ ] download the docker-image zip and extract itsaaa
- [ ] import the archive to your docker images with ```docker import <your_image>:latest' < image.tarsaaasssafd
as
as long as the image name matches the docker composr fileyou can start with ```docker compose up -d```fdgdfgfadssnss
the container will run and serve your content from buildpublishs
currently confiugred to expose port 8888 - this can be changeds
..aa 
http://localhost:8888/s
a
```s
services:
  maverick1542:asss
    image: maverick1542/web:latest
    container_name: web
    hostname: web
    ports:
      - 8888:80
```

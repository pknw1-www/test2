# template-docker-www

## setup
- [X] Create a repository from the template

## publish (Mobirise)
- [X] clone to local machinesa
- [X] checkout a new branch
- [X] publish web content into the ```publish``` foldersss
- [x] verify pusha
- [X] merge into main when happy
- [X] execute the build github action
- [ ]   VEFY IMPORTANT - the image name has to escape the slash in the image name so it should be ```maverick1542\/web:latest```
- [ ] this will ctreatem a ```docker-compose.yml``` filedfggfdgfgdffgd
- [ ] this will create a docker image (named as you input)sss
- [ ] once completed click on the Workflow summary and you'll see 2 artifactssss
ssa
## publish (3rd Party)sdfsdfsfdsdfsdsa
- [X] download the docker-compose zip and extract sss
- [ ] download the docker-image zip and extract its
- [ ] import the archive to your docker images with ```docker import <your_image>:latest' < image.tarsaaasssa
a
as long as the image name matches the docker composr fileyou can start with ```docker compose up -d```fdgdfgfadss
the container will run and serve your content from buildpublish
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

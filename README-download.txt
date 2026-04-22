Rebuild:
cat planka.tar.part.* > planka.tar
docker image load -i planka.tar

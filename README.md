# Polling_Platform
http://www.kwoksys.com/wiki/index.php?title=Moving_PostgreSQL_%28from_Windows_to_Linux%29

sudo su postgres ;
createdb world_of_polls;
psql  world_of_polls < world_of_polls.backup;

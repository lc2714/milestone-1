# milestone-1

Steps :
1. install the wsl using the command wsl --install in commond prompt/ power shell
2. after installing  change the version from 1 to version 2 
3. Then install the docker window and signup the docker window before that restart the computer
4. Now install the the gitbash for windows
5. And type the command cvat inorder to open the cvat. the commands are as follows
6. git clone https://github.com/opencv/cvat
7. cd cvat
8. docker-compose up -d
9. winpty docker exec -it cvat_server bash -ic 'python3 ~/manage.py createsuperuser'
10. enter the username and password
11. Make sure the docker window is ruuning parallel.
12. now we can find that cvat is ruuning and is shiwn in docker window.
13. Installation is done .

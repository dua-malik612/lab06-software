# Challenge: Install It Yourself

1. htop shows live CPU and memory use and the running processes.
Command: sudo apt install -y htop, then htop (quit with q)

2. Ubuntu offers apache2 version VERSION.
Command: apt show apache2

3. NUMBER packages are installed on my server now.
Command: apt list --installed | wc -l

4. Printed Hello from Alpine.
Command: sudo docker run --rm alpine echo "Hello from Alpine"

5. Docker key: /etc/apt/keyrings/docker.asc
Docker sources file: /etc/apt/sources.list.d/docker.sources
Command: ls /etc/apt/keyrings/ and ls /etc/apt/sources.list.d/

6. htop is removed. After hash -r, bash says the command is not found.
Command: sudo apt remove -y htop, hash -r, htop

# **Ansible**: hw-14

## How to:

1. ```
   ./setup.sh
   ```
2. ```
   ansible-playbook -i hosts -u root run.yml
   ```
3. ```
   docker exec -it ansible_node1 cat /tmp/test1
   ```
4. ```
   docker exec -it ansible_node2 cat /tmp/test1
   ```
5. ```
   docker exec -it ansible_node1 cat /tmp/test2
   ```
6. ```
   docker exec -it ansible_node2 cat /tmp/test2
   ```

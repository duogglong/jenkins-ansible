## Ansible hands-on lab
### I, Install ansible
- Install virtualenv
  ```
  Linux: sudo apt install python3-virtualenv
  Windows: python3 -m venv myenv
  ```
- Activate virtualenv
  ```
  Linux: virtualenv venv && source venv/bin/activate
  Windows: .\myenv\Scripts\activate
  ```
- Install ansible inside virtualenv
  ```
  pip install ansible
  ```
- Test ansible installation:
  ```
  ansible --version
  ```

### II, Install collection
- Install community.docker
  ```
  ansible-galaxy collection install community.docker
  ```
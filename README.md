##### Nginx & Brotli for CentOS

- ##### Step 1:Dwonload Nginx
  ``` bash
  git clone https://github.com/z41z/nginx
  ```

- ##### Step 2:Create link files
  ``` bash
  ln -s /usr/local/nginx/sbin/nginx /usr/bin/nginx
  ```

- ##### Step 3:Run Nginx
  ``` bash
  nginx
  ```
  `No permission` try run `chmod 777 /usr/local/nginx/sbin/nginx`
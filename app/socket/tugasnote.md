# program

# backend

- node.js `untuk server mirip php`
library :
    - socket.io     `untuk realtime koneksi`

- database :
    - redis ( in memory database ) : adapter socket.io   `supaya bisa create room`
    - mongodb ( nosql ) `untuk data user`
            * user
                ```
                username
                password
                socialId
                picture
                ```
            * room
                ```
                title
                connections
                ```

# fungsi

## guest
- daftar

## user
- login
- create room
- login


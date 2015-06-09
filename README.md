#API

###√ ACCOUNT
####√ Register
```
POST    /account/register
            - firstname
            - lastname
            - password
            - email
```
####√ Login
```
POST    /account/login
            - email
            - password
```
####√ DEVICE REGISTER
```
POST    /registerdevice
            - uuid
            - model
            - platform
            - os_version
            - app_version
```
##V1 API
####Parent
```
/api/v1/parent
    GET     /:id
    POST    /:id/addchild
                - name
    POST    /:id/changepassword
                - old_password
                - new_password
    GET     /:id/getchild/:id
    GET     /:id/getchildren
```
####Child
```
/api/v1/child
    GET     /:id
    POST    /:id/addgame
    GET     /:id/getgames
```
####Device
```
/api/v1/device
    GET     /:id
```
####Game
```
/api/v1/game
    GET     /:id
    GET     /:id/getsettings
    POST    /create
        - name
        - owner
    POST    /:id/update
        -data
        -data

```
# Exercise 2
### Build and run docker playbook
`ansible-playbook BuildAndRunContainer.yml -i inventory`

Playbook ran successfully. Now we have a ssh host on our laptop.

checkout http://localhost:10080/index.html

`ssh root@127.0.0.1 -p 10022`


### Update our application

`ansible-playbook updateApp.yml -i inventory`

In docker reload nginx
`nginx`
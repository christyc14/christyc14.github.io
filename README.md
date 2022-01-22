# Portfolio

## How to create a custom subdomain eg [finance.christychan.cc](https://finance.christychan.cc) or [tech.christychan.cc](https://tech.christychan.cc)
1. `cp <old folder> <new folder>`
2. `cd <new folder>`
3. `rm -rf .git`
4. In browser go to [github.new](https://github.new)
5. Follow instructions to create new repo.
6. Go to [Namecheap](https://namecheap.com)
7. Domain List -> christychan.cc -> Manage -> Advanced DNS -> Add New Record
8. Enter the following:
    - Type: CNAME Record
    - Host: <tech/finance/etc>
    - Target: christyc14.github.io
    - TTL: Automatic
9. Go back to the newly created github repo
10. Change the CNAME file in repo to `<tech/finance/etc>.christychan.cc`
11. Settings -> Pages -> Custom Domain Name -> `<custom subdomain>` eg `tech.christychan.cc`
12. Enable HTTPS

# Installation Guide
Create codespace from repository.

After container for codespace is built, run the following command.

npm install

npm install @medusajs/medusa-cli -g

medusa migrations run

medusa seed --seed-file=data/seed.json

medusa develop

# check background
You can check if backend is installed correclty by doing this command in your terminal. 

curl localhost:9000/store/products

And the result will be displayed as a Json formats.

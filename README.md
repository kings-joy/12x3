# Installation Guide
Create codespace from repository.

After container for codespace is built, run the following command.

npm install
npm install @medusajs/medusa-cli -g
medusa migrations run
medusa seed --seed-file=data/seed.json
medusa develop

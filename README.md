# Crawl website use Selenium with Nodejs
* Dockerzing Selenum grid system.
* Crawl all products from first page of taobao.com's category using Nodejs.
## How to run
01. `$ npm install`
02. `$ docker-compose up`
03. `$ docker-compose exec app bash -c "cd /app && node server.js \"category_url\" \"destination_file_name\""`
# nodeserver
server node


#server create commands

1.npm install express-generator -g
2.express appname
3.npm install
4.npm install -g sequelize-cli
5.npm install -g sequelize-cli
6.npm install --save mysql //for mysql
7.npm install --save pg pg-hstore //for postgrace
8.create .sequelizerc file and add following code
{

const path = require('path');
module.exports = {
  "config": path.resolve('./config', 'config.json'),
  "models-path": path.resolve('./models'),
  "seeders-path": path.resolve('./seeders'),
  "migrations-path": path.resolve('./migrations')
};

}

9.sequelize init

 var push = require('git-push');
 
push('./', 'https://github.com/NehaKhairnar/docker-compose-demo.git', function() {
  console.log('Done!');
});
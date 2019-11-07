# npms

#filtering
NPM : only 

Usage : 
var obj = {
  name: 'tobi',
  last: 'holowaychuk',
  email: 'tobi@learnboost.com',
  _id: '12345'
};
 
var user = only(obj, 'name last email');

Output : 
{
  name: 'tobi',
  last: 'holowaychuk',
  email: 'tobi@learnboost.com'
}


url : https://www.npmjs.com/package/only


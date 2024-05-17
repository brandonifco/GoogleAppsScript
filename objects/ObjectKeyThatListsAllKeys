/**
 * This code snippet is used to create an object key/value pair inside of an object where the key is "keylist"
 * and the value is an array containing the all of the keys of the object EXCEPT "keylist".
 */
function listAllOfTheKeysExceptKeylist() {
  var object = {
    keylist: function () {
    var x = Object.keys(this);
    const index = x.indexOf('keylist');
    if (index > -1) { // only splice array when item is found
      x.splice(index, 1); // 2nd parameter means remove one item only
    }
    return x;
    },
    key1: 'a',
    key2: 'b',
    key3: 'c'
  }
  Logger.log(object.keylist());
}

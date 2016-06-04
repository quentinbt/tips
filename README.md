# tips
Some usefull reminder

##Server side
### How to remotly mount file using sshf and a RSA certificate
sshfs root@52.11.68.114:/tomount /mounted -o IdentityFile=~/.ssh/udacity_key.rsa -p2200

##Git
create a new repository on the command line


  echo "# test" >> README.md
  
  git init
  
  git add README.md
  
  git commit -m "first commit"
  
  git remote add origin https://github.com/quentinbt/test.git
  
  git push -u origin master
  
…or push an existing repository from the command line


  git remote add origin https://github.com/quentinbt/test.git
  
  git push -u origin master

## Js

Get unique:
+ via filter
function onlyUnique(value, index, self) { 
    return self.indexOf(value) === index;
}

+ via prototype
Array.prototype.getUnique = function() {
    return [...new Set( [this] )];
};

// usage example:
var a = ['a', 1, 'a', 2, '1'];
var unique = a.filter( onlyUnique ); // returns ['a', 1, 2, '1']

##Other
### how to make your Markdown
https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet

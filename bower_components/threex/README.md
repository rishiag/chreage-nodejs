THREEx v2 - guidelines to write extensions for three.js 

threex-v2 is an light extension system for three.js.
It isnt really a system, it is more a convention.
There provides no code, no tool for command lines.
It is guidelines how to write modules.

It is very vendor.js

i porting all my three.js code in it.

and i have quite a few by now.


It has no specific requirement about module management, how you get them, 
or how to load them.
You can use the way you like.
It is fitting well with ```package.require.js``` module management tho.
```package.require.js``` handle packages loading with require.js, another time only guidelines, very vendor.js.
You can store your extension the way you like.
If you pick npm, see ```npm4require``` guidelines, another which is vendor.js.
You can store and publish your packages thru npm, module mangement for node.js.

[readme driven development](http://tom.preston-werner.com/2010/08/23/readme-driven-development.html)

the old threex is in [jeromeetienne/threex](https://github.com/jeromeetienne/threex-v0)

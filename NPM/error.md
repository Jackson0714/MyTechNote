user@wt01084-048:~/project/scrm/doc$ npm run build

> knowledge-base@1.0.0 build /home/user/project/scrm/doc
> ./node_modules/.bin/vuepress build


/home/user/project/scrm/doc/node_modules/vuepress/bin/vuepress.js:9
    `\n[vuepress] minimum Node version not met:` +
    ^
SyntaxError: Unexpected token ILLEGAL
    at Module._compile (module.js:439:25)
    at Object.Module._extensions..js (module.js:474:10)
    at Module.load (module.js:356:32)
    at Function.Module._load (module.js:312:12)
    at Function.Module.runMain (module.js:497:10)
    at startup (node.js:119:16)
    at node.js:902:3
npm ERR! weird error 8
npm WARN This failure might be due to the use of legacy binary "node"
npm WARN For further explanations, please read
/usr/share/doc/nodejs/README.Debian
 
npm ERR! not ok code 0

## 解决方案
使用 root 账户
sudo su 
npm run build

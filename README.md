Guide to manually install puppeteer


A: DOWNLOAD PACKAGES:
---------------------

0) Get Chromium   
   https://www.chromium.org/getting-involved/download-chromium   
   Test with: chrome-win32.zip

1) Get Node.JS from official site   
   https://nodejs.org/en   
   Test with: node-v8.10.0-win-x86.zip
   
Note:   
   For points 2 to 37, you can directly grab a package version:   
   https://github.com/collicalex/test/blob/master/node_modules.zip
   
   

2) Get Puppeteer from github release page   
   https://github.com/GoogleChrome/puppeteer/releases   
   Test with: puppeteer-1.2.0.zip

   
Note:   
   For all the below module (point 3 to 37)   
   The correct version to use or each module are in "package.json" of puppeteer.   
   But I've successfully use the latest version of each one, except for "mime" module.   
   Pupperteer need mime version 1.3.4; the latest version available is 2.0.3; but we can use the version 1.4.1

   
3) Get module debug   
   https://github.com/visionmedia/debug/releases   
   Test with: debug-3.1.0.zip
   
4) Get module ms   
   https://github.com/zeit/ms/releases   
   Test with: ms-2.1.1.zip   
   
5) Get module rimraf   
   https://github.com/isaacs/rimraf/release   
   Test with: rimraf-2.6.2.zip   
   
6) Get module glob   
   https://github.com/isaacs/node-glob/releases   
   Test with: node-glob-7.1.2.zip
   
7) Get module fs.realpath   
   https://github.com/isaacs/fs.realpath/releases   
   Test with: fs.realpath-1.0.0.zip
   
8) Get module minimatch   
   https://github.com/isaacs/minimatch/releases   
   Test with: minimatch-3.0.4.zip   
   
9) Get module  brace-expansion   
   https://github.com/juliangruber/brace-expansion/releases   
   Test with: brace-expansion-1.1.11.zip
   
10) Get module concat-map   
   https://github.com/substack/node-concat-map/releases   
   Test with: node-concat-map-0.0.1.zip
	
11) Get module  balanced-map   
   https://github.com/juliangruber/balanced-match/releases   
   Test with: balanced-match-1.0.0.zip
   
12) Get module inherits   
   https://github.com/isaacs/inherits/releases   
   Test with : inherits-2.0.3.zip
	
13) Get module  path-is-absolute   
   https://github.com/sindresorhus/path-is-absolute/releases   
   Test with: path-is-absolute-1.0.1.zip

14) Get module inflight   
   https://github.com/npm/inflight/releases   
   Test with: inflight-1.0.6.zip
	
15) Get module  wrappy   
   https://github.com/npm/wrappy/releases   
   Test with: wrappy-1.0.2.zip
	
16) Get module once   
   https://github.com/isaacs/once/releases   
   Test with: once-1.4.0.zip

17) Get module extract-zip   
   https://github.com/maxogden/extract-zip/releases   
   Test with: extract-zip-1.6.6.zip
	
18) Get module yauzl   
   https://github.com/thejoshwolfe/yauzl/releases   
   Test with: yauzl-2.9.1.zip
	
19) Get module  fd-slicer   
   https://github.com/andrewrk/node-fd-slicer/releases   
   Test with: node-fd-slicer-1.0.1.zip
	
20) Get module pend   
   https://github.com/andrewrk/node-pend/releases   
   Test with: node-pend-1.2.0.zip
	
21) Get module buffer-crc32   
   https://github.com/brianloveswords/buffer-crc32/releases   
   Test with: buffer-crc32-0.2.13.zip
	
22) Get module  mkdirp   
   https://github.com/substack/node-mkdirp/releases   
   Test with: node-mkdirp-0.5.1.zip
	
23) Get module concat-stream   
   https://github.com/maxogden/concat-stream/releases   
   Test with: concat-stream-1.6.2.zip
	
24) Get module readable-stream   
   https://github.com/nodejs/readable-stream/releases   
   Test with: readable-stream-2.3.5.zip

25) Get module process-nextick-args   
   https://github.com/calvinmetcalf/process-nextick-args/releases   
   Test with: process-nextick-args-2.0.0.zip
	
26) Get module  isarray   
   https://github.com/juliangruber/isarray/releases   
   Test with: isarray-2.0.4.zip
	
27) Get module: safe-buffer   
   https://github.com/feross/safe-buffer/releases	   
   Test with: safe-buffer-5.1.1.zip
	
28) Get module  core-util-is   
   https://github.com/isaacs/core-util-is/releases   
   Test with: core-util-is-1.0.2.zip
	
29) Get module util-deprecate   
   https://github.com/TooTallNate/util-deprecate/releases   
   Test with: util-deprecate-1.0.2.zip

30) Get module: buffer-from   
   https://github.com/LinusU/buffer-from/releases   
   Test with: buffer-from-1.0.0.zip
	
31) Get module node-https-proxy-agent   
   https://github.com/TooTallNate/node-https-proxy-agent/releases   
   Test with: node-https-proxy-agent-2.2.0.zip
	
32) Get module: agent-base   
   https://github.com/TooTallNate/node-agent-base/releases   
   Test with: node-agent-base-4.2.0.zip
	
33) Get module: es6-promisify   
   https://github.com/digitaldesignlabs/es6-promisify/releases   
   Test with: es6-promisify-5.0.0.zip
	
34) Get module: proxy-from-env   
   https://github.com/Rob--W/proxy-from-env/releases   
   Test with: proxy-from-env-1.0.0.zip
	
35) Get module: ws   
   https://github.com/websockets/ws/releases   
   Test with: ws-5.1.0.zip
	
36) Get module: async-limiter   
   https://github.com/strml/async-limiter   
   Test with: async-limiter-master.zip
	 
37) Get module: mime   
   https://github.com/broofa/node-mime/releases   
   Test with: node-mime-1.4.1.zip   
   !!!! It's not the latest version !!!!
   


   
   
   
B: INSTALL:
-----------

1) Uncompress node.zip   
   It will create a directory node-v8.10.0-win-x86

Note: If you grab my package version (node_modules.zip), just unzip its content into node-v8.10.0-win-x86\node_modules director; instead of doing points 2, 3, 4. Still need to do point 5.

2) a) Uncompress puppeteer-1.2.0.zip into node-v8.10.0-win-x86\node_modules   
      It will uncompress a directory node-v8.10.0-win-x86\node_modules\puppeteer-1.2.0   
   b) Rename it into node-v8.10.0-win-x86\node_modules\puppeteer   
      --> Puppeteer is a "module" of nodejs
   
3) a) Uncompress debug-3.1.0.zip into node-v8.10.0-win-x86\node_modules   
      It will uncompress directory node-v8.10.0-win-x86\node_modules\debug-3.1.0   
   b) Rename it into node-v8.10.0-win-x86\node_modules\debug   
      --> debug is a "module" of nodejs, which is used by puppeteer
   
4) Install all others modules from 4 to 37 as the same way   
   The node_modules directory must contains all theses 37 directories in it: 
   
   agent-base   
   async-limiter   
   balanced-match   
   brace-expansion   
   buffer-crc32   
   buffer-from   
   concat-map   
   concat-stream   
   core-util-is   
   debug   
   es6-promisify   
   extract-zip   
   fd-slicer   
   fs.realpath   
   glob   
   https-proxy-agent   
   inflight   
   inherits   
   isarray   
   mime   
   minimatch   
   mkdirp   
   ms   
   npm   
   once   
   path-is-absolute   
   pend   
   process-nextick-args   
   proxy-from-env   
   puppeteer   
   readable-stream   
   rimraf   
   safe-buffer   
   util-deprecate   
   wrappy   
   ws   
   yauzl
       
	   
5) Uncompress chrome-win32.zip where you want
	   
	   
C: Usage :
----------

1) Your js script must be at the root directory of node: node-v8.10.0-win-x86.

2) Here is a typicall script to use the portable version of chromium, ie to define the path of chrome:

```javascript
const puppeteer = require('puppeteer');

async function getPic() {
  const browser = await puppeteer.launch({executablePath: 'D:/Téléchargements/chrome-win32/chrome.exe'});
  const page = await browser.newPage();
  await page.goto('https://google.com');
  await page.screenshot({path: 'google.png'});

  await browser.close();
}

getPic();
```

3) It must be run via command prompt: 
   node-v8.10.0-win-x86>node.exe test.js

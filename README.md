# web-issues
web端常见的问题
___
问题描述：
ERROR: Failed to download Chromium r722234! Set "PUPPETEER_SKIP_CHROMIUM_DOWNLOAD" env variable to skip download.
{ Error: read ECONNRESET
    at TLSWrap.onStreamRead (internal/stream_base_commons.js:111:27)
解决方案：
在命令窗口里面直接输入；env PUPPETEER_SKIP_CHROMIUM_DOWNLOAD=true npm i puppeteer
参考地址：
[https://github.com/puppeteer/puppeteer/issues/2262]（https://github.com/puppeteer/puppeteer/issues/2262）
___


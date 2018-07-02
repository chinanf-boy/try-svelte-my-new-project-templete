
*嘘🤫  - 寻找可共享的组件模板?去这里 - >[sveltejs /组件模版](https://github.com/sveltejs/component-template)*

* * *

# svelte app

这是一个项目模板[svelte](https://svelte.technology)应用. 它住在<https://github.com/sveltejs/template>. 

使用[degit](https://github.com/Rich-Harris/degit)基于模板创建新项目

```bash
npm install -g degit # you only need to do this once

degit sveltejs/template svelte-app
cd svelte-app
```

*请注意,您需要拥有[Node.js](https://nodejs.org)安装.*

## Get started

安装依赖关系...

```bash
cd svelte-app
npm install
```

...然后开始[rollup](https://rollupjs.org): 

```bash
npm run dev
```

导航[本地主机: 5000](http://localhost:5000). 您应该会看到您的应用正在运行,

在`src`中编辑组件文件,保存它,并重新加载页面以查看您的更改. 

## Deploying to the web

### With [now](https://zeit.co/now)

安装`now`, 如果你还没有: 

```bash
npm install -g now
```

然后,从您的项目文件夹中: 

```bash
now
```

作为替代,使用[ now 桌面客户端](https://zeit.co/download), 只需将解压缩的项目文件夹拖到任务栏图标即可. 

### With [surge](https://surge.sh/)

安装`surge`, 如果你还没有: 

```bash
npm install -g surge
```

然后,从项目文件夹中: 

```bash
npm run build
surge public
```

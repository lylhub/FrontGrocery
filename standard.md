## 技术方案文档规范

书写技术方案时应对下面几点内容进行阐述，尽量避免列举关键字。可适当的增加图形描述。

### 项目相关人员（可存放在`README.md`）

0. 前端开发人员；
0. 后端开发人员；
0. 测试人员；
0. 需求方；

### 底层技术选型

1. 底层框架（React，Angular，Vue等）；
2. 构建工具；
3. 脚手架工具；

### 第三方依赖

1. 依赖其他项目（登录，订单等）；

### 相关地址（可存放在`README.md`）

1. 需求文档地址；

2. 接口文档地址；

3. 项目日常环境，预发环境，线上环境地址；（可开发完成以后补充）

   > 如果地址有其他依赖关系也需要详细阐述。
   >
   > html后缀一定要补充上，支持https的地址，默认贴出https地址。

### 版本管理及发布

1. 项目版本管理；
2. 发布方式；

### 兼容性

1. 兼容的系统版本与浏览器版本；

### 目录结构

1. 目录划分；
2. 每级目录说明；

### 页面

1. 语言类型（html，php，node）；
2. 压缩工具；
3. 模板引擎；

### CSS

1. 预处理工具（less，sass，stylus）；
2. 后处理工具（autoprefix，postcss）；
3. 压缩工具；
4. 适配方式；
5. 基础库；
6. 分层以及如何组织代码 `重要`；

### JS

1. 模块规范（amd，cmd，commonjs）；
2. 压缩工具；
3. 模板引擎；
4. 基础类库；
5. 组件的划分；
5. 分层以及如何组织代码 `重要`；

### 安全 `重要`

1. 项目中存在安全的问题点；
2. 针对问题点的解决方案；
3. 后续code review 尤其针对问题点review；

### 图片

1. 图片压缩工具；
2. 图片使用规范（CDN，base64等）；
3. 图片合并工具；

### 静态资源版本管理

1. 版本管理方式。（文件hash，版本目录hash）；

### 接口规范

如果接口规范由前端给出，则需在方案中阐述。如果由后端给出，则需对接口文档地址以及接口中需要注意的点进行说明。

1. 依赖的接口列表；
2. 接口的数据规范，输入及输出；
3. 请求方式；
4. 跨域方式；

### 相关命令

1. 相关起服务，构建，发布等命令；

### 代码检查

1. 代码检查工具（css，js）；
2. 检查规范；

### 代码文档生成

1. 代码文档生成工具；

### 不确定的问题（可存放在`README.md`）

由于还未到具体实现，所以在前期会有不确定的点，也可以在技术方案中阐述。需在确定后更新状态。
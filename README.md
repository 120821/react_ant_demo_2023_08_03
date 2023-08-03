refer: [参考ant教程](https://ant.design/docs/react/getting-started-cn).
### 1.安装和初始化
```
npx create-react-app antd-demo --template typescript
```
### 2.尝试启动
(1)进入目录：
```
cd antd-demo/
linlin@linlin-i5:/workspace/react_learn/antd-demo$
```
(2)启动：
```
npm run start
```
### 3.引入ant

```
npm install antd --save
added 68 packages in 5s
```

### 修改src/App.js，使用ant

如果你是App.js:
```
import { Button } from 'antd';
import React from 'react';

const App: React.FC = () => (
  <div className="App">
    <Button type="primary">Button</Button>
  </div>
);

export default App;

```

如果你是App.txs:
```
import { Button } from 'antd';
import React from 'react';

const App: React.FC = () => (
  <div className="App">
    <Button type="primary">Button</Button>
  </div>
);

export default App;
```
不用重新启动就可以看到页面出现了一个蓝色的按钮。

- [x] 编写测试，allFeeds 对象里面的所有的源来保证有链接字段而且链接不是空的

      遍历 `allFeeds` 确保其有 `url` 属性而且属性非空

- [x] 编写测试，allFeeds 对象里面的所有的源来保证有名字字段而且不是空的

      遍历 `allFeeds` 确保其有 `name` 属性而且属性非空

- [x] 写一个叫做 `"The menu"` 的测试组

- [x] 编写测试，测试菜单元素默认是隐藏的

      尝试用 `$` 选择隐藏菜单 `.menu-hidden`

- [x] 编写测试，当点击图标的时候菜单是否显示，再次点击的时候是否隐藏

      点击菜单按钮 `.icon-list`

      尝试用 `$` 选择隐藏菜单

      再次点击菜单按钮

      尝试用 `$` 选择隐藏菜单

- [x] 写一个叫做 `"Initial Entries"` 的测试组

- [x] 编写测试，保证 `loadFeed` 函数被调用而且工作正常，即在 `.feed` 容器元素里面至少有一个 `.entry` 的元素

      `loadFeed`函数调用完后，尝试用 `$` 选择 `.feed` 下的 `.entry`

- [x] 写一个叫做 `"New Feed Selection"` 的测试组

- [x] 编写测试，保证当用 `loadFeed` 函数加载一个新源的时候内容会真的改变

      `loadFeed`函数调用完后，获取当前 `.feed` 下的**html内容**，再次用 `loadFeed` 加载不同的内容，加载完后，对比前后html内容的不同

      发现出错，原因是超时，我们将等待时间延长到5000ms，重新测试

- [x] `README` 文档含有成功运行应用的所有详细步骤。

- [x] 设有能有效解释较长代码程序的注释。

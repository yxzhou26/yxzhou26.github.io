---
title: 格式测试 - Code, Image, LaTeX
author: Test
description: 这是一个用于测试各种Markdown格式的文章，包括代码块、图片、LaTeX公式等。
pubDatetime: 2026-01-21T00:00:00Z
slug: format-test
featured: false
draft: false
tags:
  - test
  - markdown
  - format
---

## 简介

这是一个用于测试各种Markdown格式的文章，包括代码块、图片、LaTeX公式等。

## 代码块示例

### JavaScript/TypeScript

```javascript
function helloWorld() {
  console.log("Hello, World!");
  return true;
}

helloWorld();
```

### Python

```python
def fibonacci(n):
    """计算斐波那契数列"""
    if n <= 1:
        return n
    return fibonacci(n - 1) + fibonacci(n - 2)

for i in range(10):
    print(fibonacci(i))
```

### HTML

```html
<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <title>示例页面</title>
</head>
<body>
    <h1>欢迎</h1>
    <p>这是一个示例页面。</p>
</body>
</html>
```

### CSS

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}

.card {
  padding: 2rem;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  background: white;
}
```

### SQL

```sql
SELECT users.id, users.name, COUNT(posts.id) as post_count
FROM users
LEFT JOIN posts ON users.id = posts.user_id
WHERE users.created_at > '2025-01-01'
GROUP BY users.id, users.name
ORDER BY post_count DESC;
```

## LaTeX 公式示例

### 行内公式

这是一个行内公式：$E = mc^2$，这是爱因斯坦的质能公式。

二次方程的判别式为 $\Delta = b^2 - 4ac$。

### 块级公式

二次方程的求根公式：

$$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$$

积分的基本定义：

$$\int_a^b f(x) \, dx = \lim_{n \to \infty} \sum_{i=1}^{n} f(x_i) \Delta x_i$$

矩阵示例：

$$A = \begin{pmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{pmatrix}$$

## 文本格式

### 强调

这是**粗体文本**和*斜体文本*。

这是***粗斜体***。

### 删除线

这是 ~~错误的~~ 删除的文本。

### 引用

> 这是一个引用。
>
> 可以有多行。
>
> > 这是嵌套引用。

## 列表

### 无序列表

- 第一项
- 第二项
  - 嵌套项 1
  - 嵌套项 2
- 第三项

### 有序列表

1. 第一步
2. 第二步
   1. 子步骤 A
   2. 子步骤 B
3. 第三步

### 任务列表

- [x] 已完成的任务
- [ ] 未完成的任务
- [ ] 另一个未完成的任务

## 表格

| 编程语言 | 发布年份 | 主要用途 |
|---------|--------|--------|
| Python | 1991 | 数据科学、自动化 |
| JavaScript | 1995 | Web 前端开发 |
| Rust | 2010 | 系统编程、安全 |
| TypeScript | 2012 | 大型 JavaScript 项目 |

## 其他元素

### 链接

这是一个[外部链接](https://example.com)。

### 水平线

---

### 代码片段（行内）

使用 `const` 关键字声明常量。

在 Python 中，使用 `import` 导入模块。

## 总结

这个测试文件展示了：
- ✅ 多种代码块语言
- ✅ 行内和块级 LaTeX 公式
- ✅ 各种文本格式
- ✅ 列表和表格
- ✅ 其他 Markdown 元素

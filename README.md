# 上海二次元购物指南

这是一个为上海交通大学闵行校区和复旦大学江湾校区的学生设计的二次元购物指南网页，提供了购买二次元周边和享受咖啡休闲的商场推荐。

![网页预览](https://upload.wikimedia.org/wikipedia/commons/thumb/1/13/Zhongshan_Park.jpg/320px-Zhongshan_Park.jpg)

## 🌟 功能特色

- 现代化渐变UI设计
- 精选三大二次元购物场所详细信息
- 显示距离交大和复旦校区的距离和预计行程时间
- 响应式设计，适配各种屏幕尺寸

## 🚀 部署指南

### 方法一：直接在浏览器中打开

最简单的方法是直接在浏览器中打开`测试网页.html`文件。

### 方法二：使用HTTP服务器

如果遇到图片无法显示的问题，可以使用HTTP服务器:

```bash
# 对于Windows用户 (使用命令提示符而非PowerShell)
cd 项目目录
npx http-server

# 对于有PowerShell限制的用户，可以设置执行策略 (需要管理员权限)
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
npx http-server
```

### 方法三：部署到GitHub Pages

1. 在GitHub上创建新仓库
2. 将文件上传到仓库:
```bash
git init
git add .
git commit -m "初始化网页"
git remote add origin 你的仓库URL
git push -u origin main
```
3. 在仓库设置中启用GitHub Pages，选择`main`分支作为源

## 📁 项目结构

- `测试网页.html` - 主要HTML文件，包含全部内容及样式
- `README.md` - 使用说明

## 🏬 包含的购物地点

1. **龙之梦购物中心** - 位于中山公园，有水豚大怪兽二次元综合社区
2. **环贸iapm商场** - 高端购物中心，周边有多家二次元店铺
3. **新世界城** - 位于市中心，有聚次元GOODS、二次三番店铺等

## 📱 浏览器兼容性

- Chrome/Edge/Safari/Firefox 最新版本
- 移动设备友好

---

© 2023 上海二次元爱好者指南 | 为交大和复旦的同学精心筛选

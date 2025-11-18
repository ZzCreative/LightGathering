# GreenWall 项目研究分析

## 项目基本信息
- **项目名称**: GreenWall
- **GitHub链接**: https://github.com/zmrlft/GreenWall
- **主要功能**: GitHub贡献图自定义绘制桌面应用
- **技术栈**: Go 1.23+, Wails框架, React/TypeScript, Node.js v22+

## 活跃度评估
- **Star数**: 754
- **Fork数**: 62
- **最近更新**: 昨天有提交
- **版本发布**: v0.7.2 (11小时前)
- **开放Issue**: 21个

## 环境配置要求
- Go 1.23+
- Node.js v22+
- Wails CLI v2.10.2
- Git

## 主要Issue分析
### 推荐贡献的Issue：
1. **#62** - 全绿按钮支持颜色调整 (3天前)
2. **比例显示问题** - 特定比例下显示异常 (最新)
3. **#55** - 图案自定义增强 (4天前)
4. **#49** - 多年份贡献图生成 (4天前)

## 开发环境配置步骤
```bash
# 安装Wails CLI
go install github.com/wailsapp/wails/v2/cmd/wails@v2.10.2

# 克隆项目
git clone https://github.com/zmrlft/GreenWall.git
cd GreenWall

# 安装前端依赖
cd frontend && npm install

# 启动开发环境
wails dev
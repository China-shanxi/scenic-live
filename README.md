# 全国景区实时风光直播站
纯静态前端项目，可部署在 GitHub Pages，在线查看云海、湖泊、雪山实时风景监控画面

## 功能
1. 多景区实时观景摄像头直播
2. 自适应分屏布局，支持全屏观看
3. 一键加载/清空所有画面
4. 深色护眼主题

## GitHub Pages 部署步骤
### 1. 新建GitHub仓库
1. 打开 Github 官网，点击右上角 New repository
2. 仓库名自定义（例如 scenic-live-view）
3. 勾选 Public（公开仓库，免费Pages）
4. 点击 Create repository

### 2. 上传文件
两种方式任选其一：
#### 方式A：网页直接上传
1. 仓库主页点击 Add file → Upload files
2. 新建两个文件 index.html、README.md，分别粘贴上方代码保存

#### 方式B：Git本地推送
```bash
# 克隆仓库到本地
git clone https://github.com/你的用户名/仓库名.git
cd 仓库名
# 放入index.html README.md
git add .
git commit -m "init 景区直播网站"
git push

# 🌸 Sci-Fi Sakura - 科幻樱花粒子特效

> 3D樱花树粒子特效，基于 Three.js + WebGL 构建

## ✨ 在线预览

**GitHub Pages:** https://lkcqswb.github.io/sci-fi-particle-effect-pages/

## 🎯 效果特点

- **3000+ 白色发光树枝**，采用分层伞状结构
- **50000+ 粉色樱花粒子**，花团锦簇、层次分明
- **20000+ 飘落花瓣**，营造浪漫夜樱氛围
- **UnrealBloom 后处理**，璀璨发光效果
- **可交互控制**，支持鼠标拖拽旋转、缩放

## 🕹️ 操作方式

| 操作 | 效果 |
|------|------|
| 鼠标左键拖拽 | 旋转视角 |
| 鼠标滚轮 | 缩放 |
| 鼠标右键拖拽 | 平移视角 |

## 🛠️ 技术栈

- **Three.js** - WebGL 3D渲染引擎
- **BufferGeometry** - 高性能粒子系统
- **Custom Shaders** - 自定义着色器实现发光效果
- **UnrealBloomPass** - 后期处理辉光效果

## 📁 文件结构

```
├── index.html          # 主页面（含完整3D粒子系统代码）
├── README.md           # 项目说明文档
├── reference.jpg       # 参考图片
└── .git/              # Git版本控制
```

## 🎨 视觉效果

### 树枝结构
- 多层分叉结构，底层最长、向内层逐渐变短
- 白色发光材质，营造神圣感
- 辐射状分叉角度，自然有机

### 樱花分布
- 内层（靠近树干）：枝条短密、花簇较少
- 外层（树冠边缘）：枝条长、花簇茂盛
- 整体呈伞状轮廓

### 色彩方案
| 元素 | 颜色 |
|------|------|
| 树干/树枝 | 亮白色 (#ffffff, #eeeeee) |
| 樱花深处 | 深粉色 (Hot Pink #ff1493) |
| 樱花中层 | 热粉色 (Hot Pink #ff69b4) |
| 樱花浅处 | 浅粉色 (Light Pink #ffb6c1) |
| 花苞/高光 | 纯白色 (#ffffff) |

## 📝 更新日志

### v2.0 - 分层优化版本
- ✅ 多层分叉结构，树枝数量翻倍
- ✅ 内层花簇密度降低，外层保持茂盛
- ✅ 飘落花瓣数量增加
- ✅ 底部短枝条点缀

### v1.0 - 基础版本
- ✅ Three.js WebGL 渲染
- ✅ 白色树干 + 粉色樱花
- ✅ Bloom 发光效果
- ✅ OrbitControls 交互

## 🙏 致谢

- [Three.js](https://threejs.org/) - WebGL 3D Library
- [Google Fonts](https://fonts.google.com/) - 字体支持

---


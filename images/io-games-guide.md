# IO游戏图片处理指南

## 图片规格要求

### 基本规格
- **尺寸**：800×600像素（4:3比例）
- **文件格式**：JPG或WebP
- **文件大小**：不超过300KB
- **分辨率**：72-150 DPI
- **色彩模式**：RGB

### 图片命名规范
- 使用有意义的文件名，如`io-game-battle.jpg`、`io-game-survival.jpg`等
- 避免使用空格和特殊字符
- 使用小写字母和连字符

## Photoshop处理步骤

### 1. 去杂色和优化
1. 打开图片
2. 选择"滤镜 > 杂色 > 减少杂色"
3. 调整参数：
   - 强度：3-5
   - 保留细节：3-5
   - 减少色彩杂色：0-30%
   - 锐化细节：0-30%
4. 点击"确定"应用效果

### 2. 调整尺寸
1. 选择"图像 > 图像大小"
2. 设置参数：
   - 宽度：800像素
   - 高度：600像素
   - 重新采样：双三次平滑
   - 分辨率：72-150 DPI
3. 确保"约束比例"选项已勾选
4. 点击"确定"应用更改

### 3. 优化色彩
1. 选择"图像 > 调整 > 色阶"
2. 调整黑场、灰场和白场滑块，增强对比度
3. 选择"图像 > 调整 > 色相/饱和度"
4. 适当增加饱和度（+10到+20）
5. 确保色彩模式为RGB

### 4. 锐化处理
1. 选择"滤镜 > 锐化 > 智能锐化"
2. 设置参数：
   - 数量：100-150%
   - 半径：0.5-1.0像素
   - 减少杂色：0-30%
3. 点击"确定"应用效果

### 5. 保存优化
1. 选择"文件 > 导出 > 快速导出为PNG"或"存储为Web所用格式"
2. 选择JPG格式
3. 设置质量：80-85%
4. 勾选"优化"选项
5. 点击"保存"

## 在线工具推荐

如果您没有Photoshop，可以使用以下在线工具：

1. **TinyPNG** (https://tinypng.com/) - 压缩图片
2. **Squoosh** (https://squoosh.app/) - 调整尺寸和压缩
3. **Canva** (https://www.canva.com/) - 简单的图片编辑
4. **Pixlr** (https://pixlr.com/) - 在线Photoshop替代品

## Midjourney提示词

### 基础提示词模板
```
A vibrant, colorful browser-based IO game interface, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

### 具体游戏类型提示词

1. **多人在线竞技游戏**：
```
Multiplayer online battle arena game interface, colorful characters, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

2. **生存类IO游戏**：
```
Survival IO game interface, colorful environment, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

3. **赛车类IO游戏**：
```
Racing IO game interface, colorful vehicles, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

4. **策略类IO游戏**：
```
Strategy IO game interface, colorful map, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

5. **射击类IO游戏**：
```
Shooter IO game interface, colorful weapons, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

6. **益智类IO游戏**：
```
Puzzle IO game interface, colorful blocks, minimalist design, clean UI, gaming elements, soft shadows, flat design, web game, 4:3 aspect ratio, high quality, detailed, --ar 4:3 --v 5
```

## 图片优化最佳实践

1. **使用`loading="lazy"`属性**：实现延迟加载，提高页面加载速度
2. **指定图片尺寸**：在HTML中设置`width`和`height`属性，减少布局偏移
3. **使用`object-fit: cover`**：确保图片正确填充容器而不变形
4. **提供替代文本**：使用有意义的`alt`属性，提高可访问性
5. **考虑使用`srcset`**：为不同设备提供不同尺寸的图片

## 图片文件清单

需要创建的IO游戏图片：

1. `io-game-battle.jpg` - 多人在线竞技游戏
2. `io-game-survival.jpg` - 生存类游戏
3. `io-game-racing.jpg` - 赛车类游戏
4. `io-game-strategy.jpg` - 策略类游戏
5. `io-game-shooter.jpg` - 射击类游戏
6. `io-game-puzzle.jpg` - 益智类游戏 
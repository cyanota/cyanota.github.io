在Unity中为粒子系统添加Sprite Mask的注意事项

如果需要在粒子系统中使用Sprite Mask，需要注意几点：
1. Mask和粒子系统对象必须在同一个层级，而不是粒子系统从属于Mask
2. 如果是在UI中使用，需要Mask具有“Rect Transform”组件
3. Sprite Mask的“Sprite”属性不能为空

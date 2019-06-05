# 抽象 svg 数据结构

## 一、生成新的 svg 对象形式数据结构流程

1. 将 svg 文件放置于 `svg/outline/` 文件夹中
2. 运行 `npm run generate` 命令，生成 svg 对象形式的数据结构

## 二、其他项目如何在不发布到 npm 的情况下，直接使用生成的 svg 对象形式的数据结构？

1. 在项目根目录中运行：`yarn link`
2. 在其他项目的根目录中运行：`yarn link abstract-svg`

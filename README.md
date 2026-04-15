# Learn_Algorithm_C

> 🎯 **目标**：系统学习C语言算法，同时深度掌握Git与GitHub协作流程  
> 👨‍💻 **作者**：嵌入式开发工程师 | 2025届毕业生 | 持续精进中

[![GitHub stars](https://img.shields.io/github/stars/kalaneke/Learn_Algorithm_C?style=social)](https://github.com/{username}/Learn_Algorithm_C/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/kalaneke/Learn_Algorithm_C?style=social)](https://github.com/{username}/Learn_Algorithm_C/network)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![C Standard](https://img.shields.io/badge/C-C99%2FC11-green.svg)](https://en.cppreference.com/w/c)

---

## 📖 项目介绍

本项目是笔者的**算法学习 + Git实战**双重训练场：

- 🧠 **算法学习**：用C语言实现经典数据结构与算法，夯实嵌入式开发核心基础
- 🌿 **Git熟练**：每一个算法提交都是一次Git操作练习，从基础命令到高级协作
- 📝 **知识沉淀**：通过代码+文档+Commit记录，构建个人技术成长轨迹

> 💡 **为什么用C语言？**  
> 作为嵌入式工程师，C语言是安身立命之本。算法学习不仅提升编码能力，更能深入理解底层内存管理、指针操作、性能优化。

---

## 🚀 快速开始

### 环境要求

```bash
# 编译器
gcc >= 9.0  或  clang >= 10.0

# 开发环境
VS Code + C/C++插件  或  CLion  或  Vim/Neovim

# Git版本
git >= 2.30
```

### 克隆仓库

```bash
# 使用HTTPS
git clone https://github.com/{your_username}/Learn_Algorithm_C.git

# 或使用SSH（推荐）
git clone git@github.com:{your_username}/Learn_Algorithm_C.git

cd Learn_Algorithm_C
```

### 编译运行

```bash
# 进入具体算法目录
cd 01_Array/01_TwoSum

# 编译
gcc -o two_sum two_sum.c -std=c11 -Wall -Wextra

# 运行
./two_sum
```

---

## 📚 学习路线图

### 第一阶段：基础夯实（第1-4周）

| 主题 | 内容 | Git练习目标 |
|------|------|-------------|
| 数组 | 双指针、滑动窗口、前缀和 | `init`, `add`, `commit`, `push` |
| 链表 | 单链表、双向链表、环形链表 | `branch`, `checkout`, `merge` |
| 栈与队列 | 顺序栈、链式栈、循环队列 | `log`, `diff`, `reset` |
| 递归 | 递归思想、尾递归优化 | `tag`, `stash` |

### 第二阶段：进阶提升（第5-8周）

| 主题 | 内容 | Git练习目标 |
|------|------|-------------|
| 树 | 二叉树、BST、AVL、红黑树 | `rebase`, `cherry-pick` |
| 图 | DFS、BFS、最短路径、最小生成树 | `remote`, `fetch` |
| 排序 | 快排、归并、堆排、计数排序 | `pull request` |
| 查找 | 二分查找、哈希表、布隆过滤器 | `issue` 管理 |

### 第三阶段：实战应用（第9-12周）

| 主题 | 内容 | Git练习目标 |
|------|------|-------------|
| 动态规划 | 背包问题、最长子序列 | `git flow` 工作流 |
| 贪心算法 | 活动选择、霍夫曼编码 | `release` 管理 |
| 字符串 | KMP、字典树、AC自动机 | `hook` 配置 |
| 综合项目 | 实现一个小型嵌入式算法库 | `CI/CD` 集成 |

---

## 🗂️ 目录结构

```
Learn_Algorithm_C/
├── 📁 01_Array/                    # 数组与字符串
│   ├── 📁 01_TwoSum/               # 两数之和
│   │   ├── two_sum.c               # 源码实现
│   │   ├── two_sum.h               # 头文件
│   │   ├── README.md               # 算法详解
│   │   └── test.c                  # 单元测试
│   └── 📁 02_SlidingWindow/        # 滑动窗口
├── 📁 02_LinkedList/               # 链表
│   ├── 📁 01_SingleLinkedList/     # 单链表实现
│   └── 📁 02_DoubleLinkedList/     # 双链表实现
├── 📁 03_StackQueue/               # 栈与队列
├── 📁 04_Tree/                     # 树结构
├── 📁 05_Graph/                    # 图算法
├── 📁 06_Sort/                     # 排序算法
├── 📁 07_Search/                   # 查找算法
├── 📁 08_DP/                       # 动态规划
├── 📁 09_Greedy/                   # 贪心算法
├── 📁 10_String/                   # 字符串算法
├── 📁 99_Projects/                 # 综合项目
├── 📁 docs/                        # 学习笔记与文档
│   ├── git_tutorial.md             # Git学习笔记
│   ├── c_notes.md                  # C语言要点
│   └── algorithm_complexity.md     # 复杂度分析
├── 📁 tools/                       # 工具脚本
│   ├── build.sh                    # 编译脚本
│   └── format.sh                   # 代码格式化
├── .gitignore                      # Git忽略文件
├── LICENSE                         # 开源协议
└── README.md                       # 本文件
```

---

## 🌿 Git学习轨迹

本仓库的每一次提交都是Git技能的刻意练习：

### 基础命令掌握
```bash
# 每日工作流程
git add .
git commit -m "feat(array): 实现双指针法解决两数之和

- 添加暴力解法 O(n²)
- 添加哈希表解法 O(n)
- 包含时间/空间复杂度分析

Closes #1"
git push origin main
```

### 分支管理实践
```bash
# 功能分支开发
git checkout -b feature/avl-tree
# ... 开发代码 ...
git add .
git commit -m "feat(tree): 实现AVL树自平衡"
git checkout main
git merge feature/avl-tree --no-ff
git push origin main
```

### 进阶技巧探索
- [ ] `git rebase -i` 整理提交历史
- [ ] `git bisect` 定位引入Bug的提交
- [ ] `git worktree` 多分支并行开发
- [ ] `.gitconfig` 个性化配置
- [ ] GitHub Actions CI/CD 集成

> 📌 **Commit Message规范**：遵循 [Conventional Commits](https://www.conventionalcommits.org/)

---

## 📝 学习记录

### 本周进度

| 日期 | 学习内容 | 代码实现 | Git操作 |
|------|----------|----------|---------|
| 04/14 | 数组基础 | ✅ Two Sum | ✅ init & first commit |
| 04/15 | 双指针技巧 | 🔄 滑动窗口 | 🔄 branch & merge |

### 里程碑

- [x] **2024.04.14** 仓库初始化，完成第一个算法
- [ ] **2024.05** 完成第一阶段（数组、链表、栈队列）
- [ ] **2024.06** 完成第二阶段（树、图、排序）
- [ ] **2024.07** 完成第三阶段（DP、贪心、字符串）
- [ ] **2024.08** 发布 v1.0 算法库

---

## 🛠️ 开发规范

### 代码规范

```c
/**
 * @file two_sum.c
 * @brief 两数之和 - 哈希表解法
 * @details
 *   给定数组和目标值，返回两数下标使和等于目标值。
 *   时间复杂度：O(n)
 *   空间复杂度：O(n)
 * 
 * @author Your Name
 * @date 2024-04-15
 * @version 1.0.0
 */

#include <stdio.h>
#include <stdlib.h>

/**
 * @brief 两数之和主函数
 * @param nums 输入数组
 * @param numsSize 数组大小
 * @param target 目标值
 * @param returnSize 返回结果大小
 * @return 结果数组（需调用者释放内存）
 */
int* twoSum(int* nums, int numsSize, int target, int* returnSize) {
    // 实现代码...
}
```

### 提交规范

```
<type>(<scope>): <subject>

<body>

<footer>
```

- **type**: `feat` | `fix` | `docs` | `style` | `refactor` | `test` | `chore`
- **scope**: `array` | `linkedlist` | `tree` | `graph` | `sort` ...
- **subject**: 简短描述（不超过50字符）

示例：
```
feat(array): 添加双指针法实现三数之和

- 先排序，后使用双指针
- 时间复杂度优化至 O(n²)
- 添加边界条件处理

Resolves #5
```

---

## 📚 推荐资源

### 算法学习
- [《算法导论》](https://book.douban.com/subject/20432061/) - 经典教材
- [LeetCode](https://leetcode.cn/) - 在线刷题
- [labuladong 的算法笔记](https://labuladong.gitee.io/algo/) - 通俗易懂的算法教程

### C语言进阶
- [《C程序设计语言》](https://book.douban.com/subject/1139336/) - K&R C圣经
- [《C和指针》](https://book.douban.com/subject/3012360/)
- [C语言内存管理](https://github.com/angrave/SystemProgramming/wiki/C%2C-Part-2:-Text-IO-and-Parser)

### Git/GitHub
- [Pro Git 中文](https://git-scm.com/book/zh/v2)
- [GitHub Skills](https://skills.github.com/)
- [Learn Git Branching](https://learngitbranching.js.org/?locale=zh_CN)

### 嵌入式相关
- [《嵌入式C语言自我修养》](https://book.douban.com/subject/34847578/)
- RT-Thread/FreeRTOS 源码分析

---

## 🤝 参与贡献

这是一个个人学习仓库，但也欢迎交流！

- 💬 **讨论**：在 [Discussions](https://github.com/{username}/Learn_Algorithm_C/discussions) 分享学习心得
- 🐛 **Issue**：发现问题请提 [Issue](https://github.com/{username}/Learn_Algorithm_C/issues)
- ⭐ **Star**：如果对你有帮助，给个Star鼓励一下

### 学习伙伴招募

如果你也是：
- 嵌入式工程师想提升算法能力
- 正在学习Git/GitHub
- 希望建立持续学习习惯

欢迎联系我，我们可以：
- 互相Review代码
- 分享学习资源
- 一起刷题打卡

---

## 📈 成长统计

![GitHub Stats](https://github-readme-stats.vercel.app/api?username={username}&show_icons=true&theme=radical)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username={username}&layout=compact&theme=radical)

---

## 📄 许可协议

本项目采用 [MIT License](LICENSE) 开源协议。

你可以自由地：
- ✅ 学习参考
- ✅ 复制修改
- ✅ 商业使用

只需保留版权声明即可。

---

## 💪 给自己的话

> "种一棵树最好的时间是十年前，其次是现在。"  
> —— 丹比萨·莫约

作为已经工作两年的嵌入式工程师，我深知：
- 技术深度决定职业天花板
- 持续学习是工程师的核心竞争力
- 记录和复盘是最高效的学习方式

这个仓库不仅是一堆代码，更是技术成长的见证。  
**坚持每日一题，坚持Git记录，坚持输出总结。**

2024，一起变强！💪

---

<p align="center">
  <a href="https://github.com/{username}/Learn_Algorithm_C">
    <img src="https://img.shields.io/badge/Made%20with-C-blue?style=for-the-badge&logo=c&logoColor=white" alt="Made with C">
  </a>
</p>

<p align="center">
  <sub>Built with ❤️ by {Your Name} | Embedded Engineer</sub>
</p>

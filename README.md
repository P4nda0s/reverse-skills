[English](README_EN.md) | 中文

# 逆向工程技能集 (Reverse Engineering Skills)

逆向工程分析技能，支持 40+ 种 AI 编程工具。

**专为 [IDA-NO-MCP](https://github.com/P4nda0s/IDA-NO-MCP) 设计** - 从 IDA 导出反编译结果，然后使用 AI 编程工具进行分析。

## 包含的技能

| 技能 | 描述 |
|------|------|
| `rev-symbol` | 从导出表/导入表或反编译代码分析函数符号 |
| `rev-struct` | 从反编译函数重建数据结构 |
| `rev-frida` | 使用现代 Frida API 生成动态插桩脚本 |
| `rev-unicorn-debug` | 使用 Unicorn 引擎模拟执行和调试指定代码片段 |
| `rev-dex-dumper` | 从运行中的 Android 应用内存中 dump DEX 文件，用于整体加固脱壳 |

## 安装

```bash
npx skills add P4nda0s/reverse-skills
```

### 更新与卸载

```bash
# 检查更新
npx skills check

# 更新
npx skills update

# 卸载
npx skills remove rev-symbol rev-struct
```

## 许可证

MIT

# 模块规划与产物

本目录按业务模块组织项目的详细规划、设计文档和验证产物。项目级目标与边界仍以根目录的 [PROJECT_PLAN.md](../PROJECT_PLAN.md) 为准。

## 目录约定

每个一级子目录代表一个业务模块。模块目录中的 `MODULE_PLAN.md` 是该模块持续维护的独立总规划，记录模块目标、边界、输入输出、子模块、验收标准和实现路线。它是后续模块设计和执行的依据，不是聊天记录或临时草稿。

子模块设计、运行记录和验证结果放在所属模块目录下，并按需要逐步建立。例如：

```text
modules/
├── README.md
├── destination-research/
│   ├── MODULE_PLAN.md
│   ├── submodules/
│   │   └── R0-task-definition.md
│   └── validation/
│       └── <case-name>.md
└── <next-module>/
    └── MODULE_PLAN.md
```

`submodules/` 和 `validation/` 等目录在确实产生相应文档时再创建，不预先堆放空目录。单次目的地项目的完整研究和创作记录，后续按项目总规划定义的单次项目记录方式管理。

## 当前模块

- [目的地研究与证据审计](destination-research/MODULE_PLAN.md)：负责主动研究目的地、审计证据、形成核心认知候选，并判断研究是否足以进入创意阶段。

新增业务模块时，应在本目录建立独立文件夹，并在本索引中登记其 `MODULE_PLAN.md`。

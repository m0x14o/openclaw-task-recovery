# 快速上手

如果你只想最快用起来，直接把下面 3 句之一复制给你自己的 OpenClaw。

## 一句话安装

> Install and enable https://github.com/m0x14o/openclaw-task-runtime in the current OpenClaw workspace: clone it into `repos/openclaw-task-runtime`, run `python3 install.py`, wire the task runtime recovery check into `HEARTBEAT.md`, and confirm it is ready.

## 一句话接入已有 skill

> Connect the `<skill-name>` skill to https://github.com/m0x14o/openclaw-task-runtime in the current OpenClaw workspace: create a `task_resume.py` adapter from the installed template, add task cards and checkpoints for long-running phases, enable heartbeat-based auto-resume only for safe phases, update the skill docs with the minimal usage, and then show me exactly how to use it.

## 一句话执行临时长任务

> Run this as a resumable long task under openclaw-task-runtime in the current OpenClaw workspace. If no skill exists yet, scaffold a temporary adapter under `tmp/task-runtime/<task-slug>/task_resume.py`, create a task card, checkpoint the safe phases, enable heartbeat auto-resume, and at minimum leave me either a final result, a partial result, or a clear block report: <在这里替换成你的任务>

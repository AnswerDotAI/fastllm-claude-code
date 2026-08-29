# Release notes

<!-- do not remove -->

## 0.0.9

### New Features

- Simplify `claude_code` provider to a pure stream adapter, letting FastLLM own chat loop execute tools instead of running them in-process ([#8](https://github.com/AnswerDotAI/fastllm-claude-code/issues/8))


## 0.0.8

### New Features

- Rewrite `claude_code` provider as a thin fastclaude adapter with in-process tools, real streamed tool results, and history reshaping ([#7](https://github.com/AnswerDotAI/fastllm-claude-code/issues/7))
- Migrate to typed `msg_parts` classes (Text/Thinking/ToolUse/ToolResult), add `max_buffer_size` ([#5](https://github.com/AnswerDotAI/fastllm-claude-code/issues/5))


## 0.0.7

### New Features

- Use the message model via aidialog ([#4](https://github.com/AnswerDotAI/fastllm-claude-code/pull/4)), thanks to [@jph00](https://github.com/jph00)
- Refactor core to use llmsurgery for deferred tool calls and session management, replacing manual stub/handling logic ([#3](https://github.com/AnswerDotAI/fastllm-claude-code/issues/3))
- Replace session module with llmsurgery.ant, add llmsurgery dependency ([#2](https://github.com/AnswerDotAI/fastllm-claude-code/issues/2))
- Extract session transcript read/write into new session module ([#1](https://github.com/AnswerDotAI/fastllm-claude-code/issues/1))


## 0.0.5

use default permission to be able to run as root


## 0.0.4

use registered claude code cost function (same as codex pricing)

## 0.0.3

fix prompt caching

## 0.0.2

missing APIError import

## 0.0.1

init

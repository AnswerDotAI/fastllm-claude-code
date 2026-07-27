# Release notes

<!-- do not remove -->

## 0.0.6

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

# agent-doc-writer-core

> Package 1: core for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-core
```

## Usage

```javascript
import { AgentDocWriterCore } from '@agent-doc-writer/agent-doc-writer-core';

const service = new AgentDocWriterCore();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

# agent-doc-writer-cli

> Package 4: cli for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-cli
```

## Usage

```javascript
import { AgentDocWriterCli } from '@agent-doc-writer/agent-doc-writer-cli';

const service = new AgentDocWriterCli();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

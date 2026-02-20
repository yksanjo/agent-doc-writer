# agent-doc-writer-connectors

> Package 5: connectors for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-connectors
```

## Usage

```javascript
import { AgentDocWriterConnectors } from '@agent-doc-writer/agent-doc-writer-connectors';

const service = new AgentDocWriterConnectors();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

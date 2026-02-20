# agent-doc-writer-monitor

> Service: monitor for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-monitor
```

## Usage

```javascript
import { AgentDocWriterMonitor } from '@agent-doc-writer/agent-doc-writer-monitor';

const service = new AgentDocWriterMonitor();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

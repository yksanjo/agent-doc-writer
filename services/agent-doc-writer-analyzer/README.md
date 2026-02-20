# agent-doc-writer-analyzer

> Service: analyzer for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-analyzer
```

## Usage

```javascript
import { AgentDocWriterAnalyzer } from '@agent-doc-writer/agent-doc-writer-analyzer';

const service = new AgentDocWriterAnalyzer();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

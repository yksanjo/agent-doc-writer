# agent-doc-writer-api

> Package 2: api for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-api
```

## Usage

```javascript
import { AgentDocWriterApi } from '@agent-doc-writer/agent-doc-writer-api';

const service = new AgentDocWriterApi();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

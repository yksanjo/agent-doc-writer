# agent-doc-writer-sdk

> Package 3: sdk for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-sdk
```

## Usage

```javascript
import { AgentDocWriterSdk } from '@agent-doc-writer/agent-doc-writer-sdk';

const service = new AgentDocWriterSdk();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

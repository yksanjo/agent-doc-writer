# agent-doc-writer-webhook

> Integration: webhook for Technical Documentation Writer

## Installation

```bash
npm install @agent-doc-writer/agent-doc-writer-webhook
```

## Usage

```javascript
import { AgentDocWriterWebhook } from '@agent-doc-writer/agent-doc-writer-webhook';

const service = new AgentDocWriterWebhook();
await service.init();
const result = await service.execute({ data: 'test' });
```

## API

- `init()` - Initialize the service
- `execute(input)` - Execute the service
- `health()` - Health check

## License

MIT

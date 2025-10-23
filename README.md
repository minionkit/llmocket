# LLMocket
> Plugs into any LLM API socket

**Release Date**: TBD

## Universal adapter for LLM APIs
LLMocket is a cross-platform SDK that provides a unified interface for any LLM provider through a single, consistent API. Like a universal travel adapter that works in any country, LLMocket lets you plug your code into OpenAI, Anthropic, Cohere, or any other LLM service without rewiring your application.

Built for developers who need to switch between models, test different providers, or avoid vendor lock-in without rewriting integration code. Whether you're running A/B tests across providers, implementing fallback chains, or just want the flexibility to migrate between services, LLMocket handles the voltage differences so your code stays the same.

The adapter design preserves access to provider-specific features through optional layered traits—use Anthropic's prompt caching, OpenAI's structured outputs, or any unique capabilities without branching code or losing portability. When features aren't available, they gracefully degrade or fall back to universal equivalents.

Available as native SDKs for JavaScript, Python, .NET, Java, and more. Use it directly in your codebase for seamless integration, or deploy the binary as a gateway for team-wide access. The modular architecture means you can layer LLMocket on top of existing LLM proxies to add recording capabilities, or use it standalone as your primary interface.

Professional-grade power monitoring comes built-in: comprehensive telemetry, request/response logging, and distributed tracing that exports to S3 for cross-run analysis. Mock/record/replay functionality makes testing deterministic, while intelligent caching reduces costs and latency.

Deploy as embedded SDK, REST gateway, development UI, or recording proxy—whatever fits your workflow. No more maintaining separate client libraries for each provider. Just plug in and start building.

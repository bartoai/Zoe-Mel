# Zoe & Mel Framework

![Zoe & Mel Framework](https://cdn.prod.website-files.com/674396c59212c6ea348b24e0/679ba85159ad0da6c471489c_New%20Project%20-%202025-01-30T162450.416.png)

> [!WARNING]
> This is a proof of concept for combining LLMs to explore the web as AI.

[![Visit Website](https://img.shields.io/badge/Website-zoeandmel.xyz-blue)](https://zoeandmel.xyz/)
[![Twitter Follow](https://img.shields.io/twitter/follow/barto_ai?style=social)](https://twitter.com/barto_ai)
[![GitHub](https://img.shields.io/badge/GitHub-bartoai-black)](https://github.com/bartoai)

## Getting Started

First, install the dependencies for this repository. This requires [pnpm](https://pnpm.io/installation#using-other-package-managers).

```bash
pnpm install
```

Next, copy the example environment variables:
```bash
cp .env.example .env.local
```

You'll need to set up your API keys:
1. Set up your environment for the Zoe framework
2. Set up your environment for the Mel framework
3. Configure additional API keys as needed

Update `.env.local` with your API keys:
- `ZOE_API_KEY`: Your Zoe framework API key
- `MEL_API_KEY`: Your Mel framework API key
- Additional configuration as needed

Then, run the development server:

```bash
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see Zoe & Mel in action.

## How It Works

Building an AI framework that combines multiple LLMs for web exploration is a complex task. The Zoe & Mel framework approaches this by:

1. Utilizing multiple LLMs in parallel
2. Coordinating web exploration tasks
3. Synthesizing results across models

![Zoe & Mel Architecture](public/architecture.png)

The framework uses a sophisticated loop that coordinates between Zoe and Mel components:

![Framework Loop](public/framework_loop.png)

### Key Technologies

- **Zoe Framework**: Handles primary LLM coordination
- **Mel Framework**: Manages web exploration and data synthesis
- **Next.js**: Provides the modern web framework foundation
- **Additional LLMs**: Enable diverse AI capabilities and reasoning

## Contributing

We welcome contributions! Whether it's:
- Adding new features
- Improving documentation
- Reporting bugs
- Suggesting enhancements

Please feel free to open issues and pull requests.

## License

Zoe & Mel Framework is open source software licensed under the MIT license.

## Connect With Us

- Website: [https://zoeandmel.xyz/](https://zoeandmel.xyz/)
- Twitter: [@barto_ai](https://twitter.com/barto_ai)
- GitHub: [bartoai](https://github.com/bartoai)

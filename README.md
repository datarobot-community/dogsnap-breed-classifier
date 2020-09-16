# Dog Breed ClasssifAIer, powered by DataRobot Visual AI

> _Find a dog. Take a photo of a dog. Describe the dog. Upload to the AI 🤖🧠☁️. Learn what breed the dog is. Easy enough with DataRobot._

This is a fun little demo app showing DataRobot's Visual AI in practice.
See the app in action: [link to deployed app](https://dogsnap.vercel.app).

Learn how it's made by following a tutorial on [DataRobot Developer portal](https://api-docs.datarobot.com/docs/dog-breed-categorization).

Project was bootstrapped using [Nitro](https://github.com/williamluke4/Nitro).

## Usage

### Prerequisites

- DataRobot account. You can request a free trial at https://datarobot.com/lp/trial.
- Vercel account with Vercel CLI set up (for deployment and API) - [https://vercel.com](vercel.com)

### Deploy the models

The training datasets are included and located in `datasets` directory. There are 5 of them, labeled `x-small` to `x-large` - based on dog weight. 
To use, you need to train and deploy all 5 models with DataRobot and use their deployment IDs in the environment variables (see steps below).

### Install and Run Dev Server

- Set up environment variables

```bash
cp env.sample .env
```

- Fill in your details into the environment variables.

- Set up Vercel project for local development

```bash
vercel init
```

- Install the dependencies:

```bash
npm install
```

- Run the development server

```bash
npm run dev
```

### Production

Locally:

```bash
  npm run build
  npm run start
```

On Vercel:

```bash
vercel --prod
```

## Development and Contributing
If you'd like to report an issue or bug, suggest improvements, or contribute code to this project, please refer to CONTRIBUTING.md.

## Code of Conduct
This project has adopted the Contributor Covenant for its Code of Conduct. See CODE_OF_CONDUCT.md to read it in full.

## License
Licensed under the Apache License 2.0. See LICENSE to read it in full.

## Amazon IVS Background Replacement Demo for Web

A demo web application intended as an educational tool to demonstrate how you can do background replacement on Amazon IVS. This demo also demonstrates how to use to a generative AI prompt to replace your background.

**This project is intended for education purposes only and not for production usage.**

**Demo:** Visit [https://prod.dqjfa2etwzoua.amplifyapp.com/](https://prod.dqjfa2etwzoua.amplifyapp.com/) to see a live demo.

### Background Replacement Workflow Diagram

<img src="background-replacement-workflow-diagram.png" alt="A diagram showing how background replacement is done in this demo web application." />

## Prerequisites

- [AWS Account](https://docs.aws.amazon.com/ivs/latest/LowLatencyUserGuide/getting-started-create-account.html)

## Running the demo

Follow these instructions to run the demo:

1. Run build script from the command line to bundle JavaScript

```
npm run build
```

2. Start a simple HTTP server from the project directory

```
python3 -m http.server -d ./
```

3. Open localhost:8000 in a web browser

## Known issues and limitations

- The application is meant for demonstration purposes and **not** for production use.
- This application is only tested and supported on the latest Desktop versions of Chrome. Other browsers and devices, including mobile browsers and smartphones, may work with this tool, but are not officially supported at this time.

## About Amazon IVS

Amazon Interactive Video Service (Amazon IVS) is a managed live streamin solution that is quick and easy to set up, and ideal for creating interactive video experiences. [Learn more](https://aws.amazon.com/ivs/).

- [Amazon IVS docs](https://docs.aws.amazon.com/ivs/)
- [User Guide](https://docs.aws.amazon.com/ivs/latest/RealTimeUserGuide/what-is.html)
- [Getting Started with IVS Real-Time Streaming](https://docs.aws.amazon.com/ivs/latest/RealTimeUserGuide/getting-started.html)
- [Learn more about Amazon IVS on IVS.rocks](https://ivs.rocks/)
- [View more demos like this](https://ivs.rocks/examples)

## Security

See [CONTRIBUTING](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This library is licensed under the MIT-0 License. See the LICENSE file.

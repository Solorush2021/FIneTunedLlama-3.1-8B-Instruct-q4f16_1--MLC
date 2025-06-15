<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Project Name</title>
    <style>
        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color: #f6f8fa;
            color: #24292e;
        }
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: #ffffff;
            padding: 30px;
            border-radius: 8px;
            box-shadow: 0 1px 3px rgba(27, 31, 35, 0.04);
        }
        h1, h2, h3 {
            color: #0366d6;
            border-bottom: 1px solid #eaecef;
            padding-bottom: 0.3em;
            margin-top: 24px;
            margin-bottom: 16px;
            font-weight: 600;
        }
        h1 {
            font-size: 2em;
            border-bottom: none;
            text-align: center;
            margin-bottom: 0;
        }
        h2 {
            font-size: 1.5em;
        }
        h3 {
            font-size: 1.2em;
        }
        p {
            margin-bottom: 16px;
        }
        code {
            font-family: SFMono-Regular, Consolas, "Liberation Mono", Menlo, Courier, monospace;
            background-color: rgba(27, 31, 35, 0.05);
            padding: 0.2em 0.4em;
            border-radius: 3px;
        }
        pre {
            background-color: rgba(27, 31, 35, 0.05);
            padding: 16px;
            border-radius: 6px;
            overflow-x: auto;
            margin-bottom: 16px;
        }
        pre code {
            background-color: transparent;
            padding: 0;
            border-radius: 0;
        }
        a {
            color: #0366d6;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .badge {
            display: inline-block;
            padding: 0.25em 0.5em;
            font-size: 0.85em;
            font-weight: 600;
            line-height: 1;
            text-align: center;
            white-space: nowrap;
            vertical-align: baseline;
            border-radius: 2px;
            color: #fff;
            margin-right: 5px;
        }
        .badge-blue { background-color: #0366d6; }
        .badge-green { background-color: #28a745; }
        .badge-gray { background-color: #6a737d; }
        .badge-orange { background-color: #f66a0a; }
        .badge-purple { background-color: #6f42c1; }

        .text-center {
            text-align: center;
        }
        .image-placeholder {
            text-align: center;
            margin: 20px 0;
        }
        .image-placeholder img {
            max-width: 100%;
            height: auto;
            border: 1px solid #eaecef;
            border-radius: 4px;
        }
        .citation {
            font-size: 0.9em;
            color: #586069;
            margin-top: 30px;
            padding-top: 15px;
            border-top: 1px solid #eaecef;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            font-size: 0.9em;
            color: #586069;
        }
        .back-to-top {
            text-align: right;
            margin-top: 20px;
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <div class="container">
        <div id="top" class="text-center">
            <h1>Your Project Name</h1>
            <p>Bringing Hardware Accelerated Language Models to Consumer Devices</p>

            <!-- Example Badges - Customize as needed -->
            <span class="badge badge-blue">Version X.X.X</span>
            <span class="badge badge-green">Build Status: Passing</span>
            <span class="badge badge-gray">License: MIT</span>
            <!-- Add links to your repo, docs, etc. here -->
            <p><a href="#">Documentation</a> | <a href="#">GitHub Repository</a> | <a href="#">Join Community (e.g., Discord)</a></p>
        </div>

        <h2>Overview</h2>
        <p>
            Significant strides have been made in generative artificial intelligence and large language models (LLMs). My work focuses on enabling high-performance, in-browser LLM inference directly on consumer devices, leveraging hardware acceleration.
        </p>
        <p>
            Everything runs inside the browser with no reliance on external servers and is accelerated with WebGPU. My project aims to bring powerful LLM operations to devices like laptops, phones, and game consoles, enhancing accessibility and enabling privacy-preserving AI applications.
        </p>
        <p>
            This project is designed as a base for building custom web applications leveraging this in-browser inference capability. It is a companion effort to broader work in universal LLM deployment across diverse hardware environments.
        </p>

        <div class="image-placeholder">
            <!-- Replace with an actual image illustrating your project's flow or capabilities -->
            <img src="placeholder_flow_diagram.png" alt="Flow Diagram Placeholder">
            <p><em>Fig 1: Illustrative flow of the in-browser LLM inference engine.</em></p>
        </div>


        <h2>Potential Opportunities of LLMs on Consumer Devices</h2>
        <p>
            Bringing LLMs directly to consumer devices unlocks a wealth of opportunities, including:
        </p>
        <ul>
            <li>
                <strong>Personalization:</strong> Creating AI companions that understand individual preferences and workflows, running securely with personal data on the user's device.
            </li>
            <li>
                <strong>Specialization and Application Integration:</strong> Integrating tailored language models into applications like games for unique, dynamic experiences directly on the console or device.
            </li>
            <li>
                <strong>Offline Support and Client-Server Hybrid Use-Cases:</strong> Enabling AI assistance during offline periods and facilitating hybrid models that offload computation locally while collaborating with cloud services.
            </li>
            <li>
                <strong>Decentralization:</strong> Exploring decentralized AI applications that harness the collective computational power of connected consumer devices.
            </li>
        </ul>

        <h2>Challenges to Deploy LLMs to Consumer Hardware</h2>
        <p>
            Enabling widespread deployment of LLMs on diverse consumer hardware presents several challenges:
        </p>
        <ul>
            <li>
                <strong>Diversity of Hardware and Software Stack:</strong> Navigating the vast array of GPUs (Nvidia, AMD, Intel, Apple), APUs, integrated graphics, and platform-specific APIs (CUDA, Rocm, Metal, OpenCL, SYCL, Direct3D, Vulkan/SPIRV, WebGPU).
            </li>
            <li>
                <strong>Continuous Demand of Machine Learning System Development:</strong> Keeping pace with rapid innovation in open-source ML models and system optimizations, requiring continuous system updates.
            </li>
        </ul>

        <h2>Machine Learning Compilation Approach</h2>
        <p>
            Machine learning compilation (MLC) offers a promising approach to address these challenges. Instead of manual optimization for each platform, MLC transforms ML models as programs through multiple steps:
        </p>
        <div class="image-placeholder">
             <!-- Replace with an actual image illustrating the MLC flow -->
            <img src="placeholder_mlc_flow.png" alt="MLC Flow Diagram Placeholder">
            <p><em>Fig 2: Typical Machine Learning Compilation flow.</em></p>
        </div>
        <p>
            This process involves representing the model's logic in an intermediate representation (IRModule), applying transformations like operator replacement, memory planning, operator fusion, and automatic kernel code generation for target platforms (Metal, CUDA, Rocm, Vulkan).
        </p>
        <p>
            The key advantage of MLC is building the IRModule once to generate optimized code for various targets, allowing for efficient memory usage planning and complementing other performance optimization techniques. My work leverages this methodology to build ready-to-use solutions for LLM deployment on diverse consumer devices.
        </p>

        <h2>ML Compilation for Language Models</h2>
        <p>
            As part of contributing to the machine learning compilation community, I've applied this methodology to build a universal solution for bringing LLMs onto a diverse set of consumer devices. This solution maps LLM models to APIs like Vulkan and Metal, covering a wide range of platforms including Windows, Linux, macOS, and even devices like a Steam Deck.
        </p>
        <div class="image-placeholder">
            <!-- Replace with an actual image illustrating deployment targets -->
            <img src="placeholder_deployment_targets.png" alt="Deployment Targets Placeholder">
            <p><em>Fig 3: MLC approach enabling LLM deployment across various platforms.</em></p>
        </div>
        <p>
            The same approach extends to mobile devices, enabling support for iOS and potentially other platforms. Utilizing WebGPU, these models can also be offloaded directly onto web browsers, demonstrated through companion projects like [Mention Your Web Demo Name, e.g., "MyWebLLM"] (similar to WebLLM). The power of this approach extends to other AI models, such as diffusion models for in-browser image generation (similar to Web Stable Diffusion).
        </p>
        <p>
            My work is built as a hackable Python flow, designed to empower others to develop and optimize performance for their own models and hardware use-cases.
        </p>

        <h2>Get Started</h2>
        <p>
            [Provide instructions on how users can install and use your project. Adapt the structure from the MLC-LLM README's "Get Started" section.]
        </p>

        <h3>Installation</h3>
        <h4>Package Manager</h4>
        <pre><code class="language-bash"># npm
npm install @your-scope/your-package-name
# yarn
yarn add @your-scope/your-package-name
# or pnpm
pnpm install @your-scope/your-package-name
</code></pre>
        <p>Then import the module in your code:</p>
        <pre><code class="language-typescript">// Import everything
import * as yourProject from "@your-scope/your-package-name";
// Or only import what you need
import { CreateYourEngine } from "@your-scope/your-package-name";
</code></pre>

        <h4>CDN Delivery</h4>
        <pre><code class="language-javascript">import * as yourProject from "https://esm.run/@your-scope/your-package-name";
</code></pre>

        <h3>Create Your Engine</h3>
        <p>
            [Adapt the instructions for creating your engine instance. Replace MLC-specific names with yours.]
        </p>
        <pre><code class="language-typescript">import { CreateYourEngine } from "@your-scope/your-package-name";

// Callback function to update model loading progress
const initProgressCallback = (initProgress) => {
  console.log(initProgress);
}
const selectedModel = "Some-Model-Name-q4f16_1-YOURPROJECT"; // Use your own model naming convention

const engine = await CreateYourEngine(
  selectedModel,
  { initProgressCallback: initProgressCallback }, // engineConfig
);
</code></pre>

        <h3>Chat Completion</h3>
        <p>
            [Adapt the instructions for invoking chat completions. Replace MLC-specific calls with yours.]
        </p>
        <pre><code class="language-typescript">const messages = [
  { role: "system", content: "You are a helpful AI assistant." },
  { role: "user", content: "Hello!" },
]

const reply = await engine.chat.completions.create({
  messages,
});
console.log(reply.choices[0].message);
console.log(reply.usage);
</code></pre>

        <h3>Streaming</h3>
        <p>
            [Adapt the instructions for streaming. Replace MLC-specific calls with yours.]
        </p>
        <pre><code class="language-typescript">const messages = [
  { role: "system", content: "You are a helpful AI assistant." },
  { role: "user", content: "Hello!" },
]

// Chunks is an AsyncGenerator object
const chunks = await engine.chat.completions.create({
  messages,
  temperature: 1,
  stream: true, // <-- Enable streaming
  stream_options: { include_usage: true },
});

let reply = "";
for await (const chunk of chunks) {
  reply += chunk.choices[0]?.delta.content || "";
  console.log(reply);
  if (chunk.usage) {
    console.log(chunk.usage); // only last chunk has usage
  }
}

const fullReply = await engine.getMessage();
console.log(fullReply);
</code></pre>

        <h2>Advanced Usage</h2>
        <p>
            [Include sections on advanced usage, adapting from the MLC-LLM README. For example, using workers, integrating with other frameworks, etc. Replace MLC-specific names and concepts with yours.]
        </p>
        <!-- Example section -->
        <h3>Using Workers</h3>
        <p>
            To optimize application performance, you can offload heavy computation to a worker script...
        </p>
        <!-- Add code examples adapted for your project -->

        <h2>OpenAI API Compatibility</h2>
        <p>
            [State your project's compatibility with the OpenAI API, listing supported functionalities like streaming, JSON-mode, etc. If applicable.]
        </p>

        <h2>Custom Models</h2>
        <p>
            [Explain how users can integrate and deploy custom models in your project's format. Refer to your project's documentation for detailed steps. Emphasize the customizable elements like model artifacts and libraries.]
        </p>
        <pre><code class="language-typescript">import { CreateYourEngine } from "@your-scope/your-package-name";

async main() {
  const appConfig = {
    "model_list": [
      {
        "model": "/url/to/my/llama",
        "model_id": "MyCustomModel-v1-q4f32_0",
        "model_lib": "/url/to/mycustommodel.wasm",
      }
    ],
  };
  // override default
  const chatOpts = {
    "repetition_penalty": 1.01
  };

  // load a custom model using the defined appConfig
  const engine = await CreateYourEngine(
    "MyCustomModel-v1-q4f32_0",
    { appConfig }, // engineConfig
    chatOpts,
  );
}
</code></pre>


        <h2>Building From Source</h2>
        <p>
            [Provide instructions on how to build your project from source. Adapt the steps from the MLC-LLM README, replacing their project names and dependencies with yours.]
        </p>
        <pre><code class="language-bash"># Assuming you have Node.js and npm installed
npm install
npm run build
</code></pre>
        <p>
            [Explain how to test local changes, similar to the MLC-LLM example.]
        </p>

        <h2>Links</h2>
        <ul>
            <li><a href="#">Demo App: [Your Demo Name]</a></li>
            <li>If you are interested in native runtime deployment, check out [Link to Your Native Project, if applicable]</li>
            <li>You might also be interested in [Link to Your Diffusion Model Project, if applicable]</li>
        </ul>

        <div class="citation">
            <p>
                If you find this project to be useful, please cite:
            </p>
            <pre><code class="language-bibtex">@misc{[your citation key],
      title={[Your Project Title]},
      author={[Your Name]},
      year={[Current Year]},
      howpublished={[Link to your project/publication]},
      note={Inspired by work in the ML compilation community}
}
            </code></pre>
        </div>

        <h2>Acknowledgement</h2>
        <p>
            [Acknowledge individuals, communities, or open-source projects that your work builds upon. Be genuine and appreciative. You can take inspiration from the structure of the MLC-LLM acknowledgement.]
        </p>
        <p>
            This project is only possible thanks to the open-source ecosystems that I stand on. I want to thank the [mention relevant communities like Apache TVM, PyTorch, Hugging Face, WebAssembly, Emscripten, WebGPU, etc.] communities. The open-source ML community members made these models publicly available.
        </p>

        <h2>Contributors</h2>
        <!-- You can link to a GitHub contributors graph if you have one -->
        <a href="#">
            <img alt="contributors" src="https://contrib.rocks/image?repo=your-github-username/your-repo-name"/>
        </a>
        <p>
            This project welcomes contributions! [Link to contribution guidelines]
        </p>


        <div class="back-to-top">
            <a href="#top">⬆ Back to Top ⬆</a>
        </div>

        <div class="footer">
            <p>© [Current Year] Your Name/Organization. All rights reserved.</p>
        </div>

    </div>
</body>
</html>

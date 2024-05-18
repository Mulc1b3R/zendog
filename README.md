# Zendog

Built using Next.js, TypeScript, and Tailwind CSS.

zendog is an interface for OpenAI's natural language machine learning models commonly known as Chat GPT ( “Generative Pre-trained Transformer”
and requires an API_KEY : https://platform.openai.com/account/api-keys
# use
Navigate to : https://zendog.vercel.app/ 
click on Open AI API Key (bottom left) paste your key into the box and click the tick symbol.

Embed : <iframe src="https://zendog.vercel.app/" width="100%" height="600px"></iframe>

Start making queries...

************************************************************************************************************************************************************************


## Mods...

Modify the chat interface in `components/Chat`.

Modify the sidebar interface in `components/Sidebar`.

Modify the system prompt in `utils/index.ts`.

## Python

To install the official Python bindings, run the following command:

```pip install openai```

## Authorization

All API requests should include your API key in an Authorization HTTP header as follows:

Authorization: Bearer OPENAI_API_KEY= your-openai-api-key

  
  Node.js (Orgs)
  
  import { Configuration, OpenAIApi } from "openai";
const configuration = new Configuration({
    organization: "org-g6Se7pwtJFzrBct5UisL7zAJ",
    apiKey: process.env.OPENAI_API_KEY,
});
const openai = new OpenAIApi(configuration);
const response = await openai.listEngines();

python ; 

import os
import openai
openai.organization = "org-g6Se7pwtJFzrBct5UisL7zAJ"
openai.api_key = os.getenv("OPENAI_API_KEY")
openai.Model.list()

##Ports:

3000 localhost...http://localhost:3000/
http: 80  (Apache)
https:443
MySQL: 3306
MariaDB: 3307 
 
## Running Locally (dev server) 

**1. Clone Repo**

```
git clone : https://github.com/Mulc1b3R/zendog.git
```

**2. Install Dependencies**

```
npm i  
```

**3. Provide OpenAI API Key**

Create a .env.local file in the root of the repo with your OpenAI API Key:

```bash
OPENAI_API_KEY=YOUR_KEY
```

**4. Run App**

```
npm run dev
```

**5. Use It**

You should be able to start chatting........ENJOY!!!

## WAMP server: 3.3.0
Apache Version:2.4.54.2:
MySQL Version:
8.0.31 
MariaDB Version:
10.10.2

Download Here : https://www.wampserver.com/en/download-wampserver-64bits/
clone the repo : git clone https://github.com/mckaywrigley/chatbot-ui.git (main) alt  https://github.com/psico-mojo/zendog (hybrid)
Install folder in root directory.
run

## Contact

mojo@psicodata.io     


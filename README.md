# QueerSafe - Safeguarding Queer Communities, Amplifying Their Voices 🌈💪🏼

QueerSafe is a Chrome extension designed to safeguard and amplify the voices of queer individuals by detecting offensive content related to them in webpages and replacing it with something positive. It utilizes sentiment analysis powered by the VADER (Valence Aware Dictionary and sEntiment Reasoner) model to identify offensive content and provide a safer online environment for the queer community.

## About this repo 💎

- Fork of the [original repo](https://github.com/mkswagger/wafflehacks).
- This repo is used to host the flask app
- Flask app hosted using Microsoft Azure Webapps.
- The Flask app is used as an API endpoint to connect the ML model.
- Fetch is used in JS on the frontend to connect with the API.
- The content is parsed and is passed through the ML model.
- The output is then returned to the frontend.

## Requirements 🔨

- Python 3.x
- NLTK (Natural Language Toolkit) library
- Flask web framework

## Feedback and Contributions ❤

We welcome your feedback and contributions to make the QueerSafe Chrome extension even better. If you encounter any issues, have suggestions for improvements, or would like to contribute to the project, please feel free to submit issues or pull requests on the project's main [GitHub repository](https://github.com/mkswagger/wafflehacks).

Together, we can create a more inclusive online space for the queer community and help amplify their voices.










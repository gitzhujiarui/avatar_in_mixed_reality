# avatar_in_mixed_reality

## About
![cover_img](Images/cover_img.png)

The `avatar_in_mixed_reality` project houses the Unity source code necessary to create an interactive human avatar for use in either virtual reality (VR) or augmented reality (AR) environments. This project has only been tested and deployed on the Oculus Quest 2 and Oculus Quest Pro headsets. The compatibility with other devices is not guaranteed. Additionally, the avatar developed through this project was featured in paper Free-form Conversation with Human and Symbolic Avatars in Mixed Reality.

### Abstract
The integration of large language models and mixed reality technologies has enabled users to engage in free-form conversations with virtual agents across different “realities”. However, if and how the agent’s visual representation, especially when combined with mixed reality environments, will affect the conversation content or user experience is not yet fully understood. In this work, we design and conduct a user study involving two types of visual representations (a human avatar and a symbolic avatar) and two mixed reality environments (virtual reality and augmented reality), facilitating a free-form conversation experience with GPT-3 powered agents. We found evidence that the use of virtual or augmented realities can influence conversation content. Users chatting with avatars in virtual reality made significantly more references to the location or the space, suggesting they tended to perceive conversations as occurring in the agent’s space, whereas the physical AR environment was perhaps more perceived as the user’s space. Conversations with the human avatar improve user recall of the conversation, even though there is no evidence of increased information extracted during the conversation. These observations and our analysis of post-study questionnaires suggest that human avatars can positively impact user memory and experience. We hope our findings and the open-source implementation will help facilitate future research on free-form conversational agents in mixed reality.

## Usage
1. Clone this repro
2. Get an OpenAI API key via https://openai.com/blog/openai-api
3. Open the project with Unity Editor Version 2021.3.11f1 SILICON LTS (not guaranteed with other editor versions)
4. In the Unity Editor, find and open the scene human_avatar_VR (human_avatar_AR for augmented reality scene)
5. In Assets > OpenAI_Unity, find EngineSettings and paste your OpenAI API key
6. Click Run button to start the application on local machine
7. Press and hold the key "m" everytime you want to converse with the agent
8. Follow this [guide](https://developer.oculus.com/documentation/unity/unity-build/) for Oculus build and deployment

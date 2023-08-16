# avatar_in_mixed_reality

## About
![cover_img](images/cover_img.png)

The `avatar_in_mixed_reality` project houses the Unity source code necessary to create an interactive human avatar for use in either virtual reality (VR) or augmented reality (AR) environments. This project has only been tested and deployed on the Oculus Quest 2 and Oculus Quest Pro headsets. Thus, compatibility with other devices is not guaranteed. Additionally, the avatar developed through this project was featured in paper Free-form Conversation with Human and Symbolic Avatars in Mixed Reality.

## Usage
1. Clone this repro
2. Get an OpenAI API key via https://openai.com/blog/openai-api
3. Open the project with Unity Editor Version 2021.3.11f1 SILICON LTS (not guaranteed with other editor versions)
4. In the Unity Editor, find and open the scene human_avatar_VR (human_avatar_AR for augmented reality scene)
5. In Assets > OpenAI_Unity, find EngineSettings and paste your OpenAI API key
6. Click Run button to start the application on local machine
7. Press and hold the key "m" everytime you want to converse with the agent
8. Follow this [guild](https://developer.oculus.com/documentation/unity/unity-build/) for Oculus build and deployment

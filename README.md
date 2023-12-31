# Mixed-Reality-Starter-Template

This is a Mixed-Reality-Starter-Template, compatible with both Meta and Apple headsets. It provides starter templates tailored for these platforms, featuring specific functionality and assets. All projects are built on Unity, ensuring seamless cross-platform compatibility, and employ C# as the scripting language.  The current template comes with passthrough and hand tracking support.

Last Updated: June 27, 2022 

Unity Version : 2022.3.2f1

## Getting Started
Using the following steps, you can set up the project on your machine and run it on your headset. This project has been setup to be compatible with upcoming VisionOS and Meta Quest OS and can bee currently deployed on any Meta Headset using the following steps. Apple Deplyment will also be added after the launch of Apple Headset.

### Software Setup

- Clone/Download the Project Repository.
- Install Unity Hub for your machine from official [Unity Site](https://unity.com/download).
- Choose Unity Version - 2022.3.2f1 and add “Android Build Support” (You can skip this step as well and do it in next to next step).
- Now, click on open under projects and navigate to the downloaded project repository.
  Unity might prompt you by saying that you do not have the correct version of Unity. Make sure you download the required version with  “Android Build Support”.
- Now once you are in Unity, from the top bar, navigate to File> Build Settings > Android
- Make sure, under “Scenes in Build”, “Scene/Starter” is selected,  and click on Switch Platform.
- Click player settings, navigate to Publishing settings and under keystore enter temporary code 123456 for keystore and allias. You can change this as well.
- That’s it, now we need to prepare our headset to run the project.

### Hardware Setup

- Follow the instructions on [Oculus Device Setup Page](https://developer.oculus.com/documentation/native/android/mobile-device-setup/) to put your device in Developer Mode

### Build App

- Now go back to Unity and under Android Build Settings, click “Refresh” and make sure you can discover your headset in the drop down. If you can’t see it, please complete the previous step.
  Select you headset and click “Build and Run”


## Assets
All projects might have some assets imported with them. These are free to use subject to the licenses attached in the folders. Please abide by the licenses before using specefic assets. Additonaly feel free to import free Assets from [Unity Asset Store](https://assetstore.unity.com/). Tip: When you might add assets, they might have a purple material. This might be because they are using standard material shader, and we are using URP for our projects. You can upgrade the materials using steps [here](https://jordancassady.medium.com/how-to-upgrade-materials-to-urp-in-unity-2021-2-and-above-3f1274656989).

## Version Control
If you are using any Unity project like this and using version control like git, make sure you only add specefic folder to you commit. "Assets", "Packages" and "Project Settings" are the three folders that you must add. Folders like "Library" are extremely heavly and are generated by Unity the first time you open the project. Additonally you might wanna add specefic folders that might have been added externally like "Builds" or "Keystore". If any of the asset file is larger than 100MB, it is also suggested using github [lfs](https://docs.github.com/en/repositories/working-with-files/managing-large-files/installing-git-large-file-storage). For any project, we suggest adding Unity .gitignore before pushing. This project comes with the gitgnore added so it is suggested to fork the repo opposed to downloading code.

## Contributing
Users are encouraged to suggest changes to the repository, esspecially for such an ever-growing field, and they can do so by suggesting changes to the author using the contact information updated on the profile page.

## License
This repository is protected under the MIT License.

Copyright (c) 2023 Mixed-Reality-Starter-Template

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

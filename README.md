# ViperTemplate
Template to generate VIPER classes on Xcode.

## About VIPER
VIPER is a backronym for View, Interactor, Presenter, Entity and Router. It’s basically an approach that implements the Single [Responsibility Principle](https://en.wikipedia.org/wiki/Single_responsibility_principle) to create a cleaner and more modular structure for your iOS project. You can learn more about it 
[in this blog post](https://www.ckl.io/blog/ios-project-architecture-using-viper/).

## Installation
- [Download VIPER Template](https://github.com/romsi/VIPERXCodeTemplate/archive/master.zip) or clone the project
- Copy the `Design Pattern` folder to `~/Library/Developer/Xcode/Templates/File Templates/` or create a symbolic link to that folder.

## Using the template
- Start Xcode and create a new group for your VIPER module
- Create a new file (`File > New > File` or `⌘N`)
- Choose `Design Pattern` and `VIPER`

## Created Files
- `Contract` -> Contains all the protocols used in VIPER
- `Interactor`
- `Presenter`
- `ViewController` (AKA View)
- `Router`

## Contact
[Natan Grando](https://github.com/natangr)

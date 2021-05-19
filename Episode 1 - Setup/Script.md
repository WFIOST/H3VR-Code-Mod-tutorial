

In this tutorial we will be:
- Installing Visual Studio, which is an IDE (Integrated Development Environment) for creating H3VR Mods
- Making a “fork” of the example mod “git” repo, and using it as a base
- Adding some debug code, and loading it into H3VR


# Let's get started!

## Part 1: Setup
____
The first step we are gonna take is installing “Visual Studio” which is the program we are going to be using to make our H3VR mod

First step, download the [Visual Studio Installer (Community edition)](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=Community&rel=16&apptype=desktop&tech=dotnetCFV&os=windows) here. Complete the setup intructions, and once the Installer launches, click "Individual Components" (*figure 1.1*)


> ![](Figure1.1.png?raw=true)
> *figure 1.1*

Check ".NET framework 3.5 development tools" (*figure 1.2*), and then press "Install"

> ![](Figure1.2.png?raw=true)
> *figure 1.2*

____
Now that we have Visual Studio installed, let us now setup our project
____
First, and this is optional, we are going to create an account with GitHub [TODO: EXPLAIN GITHUB]
____
### TODO: write github setup instructions
____

Now that we have github setup, head to [this repository](https://github.com/Maiq-The-Dude/EmptyDeliMod). Now if you have already setup a Github account, you can just press the button that says "Use template". Fill out the name for your mod, and I reccomend that you keep the mod public.
Now, press the green and white arrow, and press the clipboard. This will copy the URL we require to the clipboard.
If you did not create a github account, you must click the green and white arrow button and copy the link we require. 

Next, open Visual Studio. Press "Clone repository" and paste in the link we copied into the first field. Choose a path for the repository and
press "Clone".

Great! We have now setup our project, and we are ready to now start writing some code!
___

## Part 2: Coding
___
Now the fun part. We are going to put some code in our mod, and later load it into H3VR to see if everything is working correctly.

On the (TODO: INSERT POS OF EXPORER HERE) side of the screen, open the directory `src` by pressing the small arrow, and then open the file `ExampleMod.cs`.

That file should look like this:
```cs
using Deli.Immediate;
using Deli.Setup;

namespace Deli.ExampleMod
{
	public class ExampleMod : DeliBehaviour
	{
		public ExampleMod()
		{

		}
	}
}
```


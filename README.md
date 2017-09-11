# Building Your Brand 

## INSTALL
Please install or check that these programs are running on your computer (Windows, Linux, Mac).
- [Visual Studio Code](https://code.visualstudio.com/) 
- [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
    - Optionally, you can install [GitHub Desktop](https://desktop.github.com/) which is a nice user interface for GitHub.
    - To check if Git is running on your computer, open Terminal/Powershell and run the command `git --version`.

## SETUP
1. Download as a ZIP or clone this repository onto your computer. 
    
    ![download](images/download.png)
2. Extract the folder somewhere convenient like "Desktop".

    ![extract](images/extract.png)
3. Open it in Visual Studio Code.
    
    ![open in vs code](images/openinvscode.png)

You should see something like this after opening the folder in Visual Studio Code.
    ![vs code](images/vscode.png)

4. Right-click on the `resume.html` file and select "Reveal in Explorer". 

    ![reveal in explorer](images/revealinexplorer.png)
5. Double-click or open the `resume.html` file in a browser to view the current site.

    ![open in browser](images/openinbrowser.png)

## ****More information provided by instructor here*** 

## BOOTSTRAP
Bootstrap is the most popular HTML, CSS, and JS framework for developing responsive, mobile first projects on the web. Let’s start with a basic template then build off it with components and code snippets to customize our own website.

1. Open a new tab in your browser and navigate to the [Bootstrap examples website](https://v4-alpha.getbootstrap.com/examples/).

2.	Try adding some of the following elements to your website from the.

| Feature  |  Type |  Function |
|---|---|---|
| [Navbar](https://v4-alpha.getbootstrap.com/examples/navbars/)  |  Component | Navigation header  |
|  [Jumbotron](https://v4-alpha.getbootstrap.com/examples/jumbotron/) | Component  |  Showcase key content |
|  [Typography](https://v4-alpha.getbootstrap.com/content/typography/) | CSS  | Different ways of displaying text  |
|[Grid System](https://v4-alpha.getbootstrap.com/layout/grid/) |  CSS |  Utilize 12-column system of Bootstrap to divide up your content |
|  [Responsive Helpers](https://v4-alpha.getbootstrap.com/utilities/responsive-helpers/) | Component  |  For documents, videos, etc. |
|  [ScrollSpy](https://v4-alpha.getbootstrap.com/components/scrollspy/) |  JavaScript | Enables functionality for the Navbar  |

## CSS
1.	In Visual Studio Code, open the file `main.css`. 
	This is being referenced in the `resume.html` file by the line: 

    `<link href="main.css" rel="stylesheet" type="text/css">`


3.	Add CSS code to `main.css` to assign style elements to tags or containers in your resume.html file. Don’t forget to use a class selector (.containername) to apply style to classes. Example (.jumbotron) below:
    ```css
    body {     
        position: relative;
    } 

    .jumbotron {
        background-color: lightblue; 
    }

    h1 {    
        font-family: Georgia;
        text-align: center;     
        font-style: italic;
        padding-top: 50px; 
    } 
    
    p {     
        font-family: Arial;     
        font-size: 20px;     
    } 
    ```

**For help with CSS syntax rules, check out https://www.w3schools.com/css/css_syntax.asp 

## AZURE
1.	To host your website in the cloud, you will need to make two new accounts:
- GitHub -> Sign up at https://github.com 
- Azure -> If using an Azure Pass, please visit [http://microsoftazurepass.com](http://microsoftazurepass.com). Otherwise, sign up at https://microsoft.azure.com for a Free Trial.
  - Azure requires a Microsoft or work/school email account (@edu, @outlook, @hotmail, etc). If you don’t have one, create one at https://signup.live.com
2.	Once you have these accounts, and your website is ready for public viewing, upload your code to a new repository in GitHub.
3.	Sign up for the free trial in Azure, then create new Web App.
4.	Point this to your GitHub master branch and voila, you’re in the cloud!





